# deeplayTestTask
Проект находится в папке TestTask
Три основных класса
Main - для запуска приложения
Solution - класс, с одной статической функцией getSolution()
GameLogic - класс, в котором прописана основная логика решения
При вызове getSolution() происходит сброка приложения и вызов отдельных функций из GameLogic
Сделано для повышения читаемости когда 

Отдельная папка для работы с данными о полях и рассах - UtilsForData
В ней - класс ExelData и документ myData.xlsx
Класс ExelData принимает на вход значение существа (строки)
Функция getData() принимает на вход значение символа (столбца) и возвращает значение согласно таблице 

в папке test класс MyTests, в котором осущественна проверка основных функций приложения 
Тесты написаны на JUnit 

Задача: 
поле 4*4 с случано расставленными значениями, имеющий свой вес.
случайный выбор пользователя, который тоже влияет на значения полей 
найти минимальный путь от начала до конца 
данные поля-пользователь хранить отдельно 