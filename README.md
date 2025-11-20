# kalkulator 

#include <iostream>

int main() {
    setlocale(LC_ALL, "RU");

    int x, y;
    char op;

    std::cout << "Введите первое число: ";
    std::cin >> x;

    std::cout << "Выберите операцию (+ или -): ";
    std::cin >> op;

    std::cout << "Введите второе число: ";
    std::cin >> y;

    int result;

    if (op == '+') {
        result = x + y;
        std::cout << "Сумма равна " << result << std::endl;
    } else if (op == '-') {
        result = x - y;
        std::cout << "Разность равна " << result << std::endl;
    }

    return 0;
}
