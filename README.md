// math_functions.cpp
#include <iostream>

int add(int a, int b) {
    return a + b;
}
// main.cpp
#include <iostream>
#include "math_functions.cpp"

int main() {
    int result = add(3, 4);
    std::cout << "The sum is: " << result << std::endl;
    return 0;
}
g++ main.cpp math_functions.cpp -o main
./main
git commit -m "Add math_functions.cpp with add function and update main.cpp to use it"
