# Отчёт о тестировании Precision

## Краткое описание

13.07.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 5 минут.

В результате тестирования выявлены следующие дефекты:
* <a href="https://github.com/xeniya-izotowa/Java2.2/issues/1"> Issue 1 Неточность округления после запятой значения переменной totalBonus </a>

## Описание процесса тестирования

В качестве тестовых данных использовались данные, предложенные в д/з из источника  <a href="https://github.com/netology-code/javaqa-homeworks/tree/master/programming"> Task 2 Precision</a>

* double regularBonus = 0.3; 
* double specialBonus = 0.6;
* double totalBonus = regularBonus + specialBonus;

**Expected Result:** Значение переменной totalBonus = 0.9.

## Тестирование производилось в следующем окружении:
* Windows 10 x64 (19042.1052)
* Java version 11.0.11