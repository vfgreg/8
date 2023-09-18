# 8
#include <iostream>
int main() {

    int *p;
    int a[] = { 1,2,3,4 };
    int(&t)[4] = a;
    std::cout << t << std::endl;

    return 0;
}
