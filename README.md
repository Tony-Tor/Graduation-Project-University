# Программный комплекс для помощи в автоматизации котла водогрейного.

Комплекс будет представлять из себя веб-приложение, 
написанное на Python с использованием фреймворка Flask, Tailwind CSS, JavaScript,
а также библиотек matplotlib (информация будет обновляться).
Аналогично будет осуществлена интеграция работы с Matlab. Также планируется создание системы API для работы с ПЛК.

## Что будет реализовано:

> Расчёт одноконтурной автоматической системы регилурования, 
а также расчёт ПИД-регулятора с помощью метода расширенных частотных характеристик.

## Функции раздела:

- Построения импульсной характеристики.
- Определения динамических параметров импульсной характеристики.
- Перестройка импульсной характеристики в разгонную характеристику объекта.
- Определенние параметров по разгонной характеристике (t, T1, T2, K).
- Нахождение параметров T1, T2 методом Ольденбурга-Сарториуса.
- Нахождение передаточной функции с помощью метода Симою.
- Построение переходных характеристик трёх моделей (с помощью Matlab).
- Определение значение дисперсии для трёх случаев (метод касательной, Ольденбурга-Сарториуса, Симою).
- Получение наиболее идентичного переходного процесса при сравнении трёх случаев выше.
- Построение плоскости параметров настройки ПИД-регулятора при подобранном C2.
- Визуализирование переходного процесса с помощью использования регулятора.
- Оценивание качество переходного процесса.

> Получение приближенных математических моделей технологического объекта
графоаналитическим методом (с настройкой ПИ-регулятора).
> 
## Функции раздела:

- Создание математической модели объекта управления.
- Построение передаточной фукнции объекта управления
- Определение степени колебательности.
- Вычисление параметров регулятора.
- Построение математической модели объекта управления с наилучшими настройками ПИ-регулятора.
- Построение графика D-разбиения параметров ПИ-регулятора.
- Построение передаточной фукнции объекта управления с использованием ПИ-регулятора.
- Определние степени затухания.
- Оценивание качества (переходного процесса, степени затухания, длительности и тд).
- Определение параметров объекта графическим методом.
- Подстановка s и получение передаточной функции вида W (m,ij)инв.
- Вычисление параметров регулятора.
- Получение математической модели объекта управления с наилучшими настройками ПИ-регулятора.
- Построение графика D-разбиения параметров ПИ-регулятора.
- Построение передаточной функции объекта с использованием ПИ-регулятора.
- Определение степени затухания.
- Построение переходного процесса в замкнутой системе регулирования по управляющему и возмущающему воздействию.

## Расчёт комбинированной системы регулирования.

- В процессе реализации.