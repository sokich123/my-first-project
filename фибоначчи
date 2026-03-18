# Запрашиваем у пользователя начало и конец диапазона
start = int(input("Введите начало диапазона: "))
end = int(input("Введите конец диапазона: "))

# Проверяем, что начало меньше конца
if start >= end:
    print("Ошибка: начало диапазона должно быть меньше конца.")
else:
    # Генерируем числа Фибоначчи
    fib1, fib2 = 0, 1
    fibonacci_numbers = []
    
    # Продолжаем генерацию, пока числа не превысят конец диапазона
    while fib1 <= end:
        if fib1 >= start:
            fibonacci_numbers.append(fib1)
        fib1, fib2 = fib2, fib1 + fib2
    
    # Выводим результат
    if fibonacci_numbers:
        print("Числа Фибоначчи в диапазоне от", start, "до", end, ":")
        print(*fibonacci_numbers)
    else:
        print("В заданном диапазоне нет чисел Фибоначчи")
