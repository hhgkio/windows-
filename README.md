#include <iostream>
int main() {
    // 这就是你未来监控程序的雏形！
    const int MAX_CPU = 100;        // 常量：上限永远不变
    int currentCpu = 75;            // 变量：模拟当前CPU占用
    int memoryUsage = 2048;         // 变量：模拟内存用了多少MB
    
    std::cout << "CPU上限: " << MAX_CPU << "%" << std::endl;
    std::cout << "当前CPU: " << currentCpu << "%" << std::endl;
    // 算算还剩多少
    int available = MAX_CPU - currentCpu;
    std::cout << "剩余CPU资源: " << available << "%" << std::endl;
    return 0;
}

