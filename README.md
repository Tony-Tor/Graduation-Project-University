# Программный комплекс для автоматизации котла водогрейного.

Комплекс будет представлять из себя веб-приложение, 
написанное на Python с использованием фреймворка Flask, Bootstrap, JavaScript,
а также библиотек Matplotlib, SciPy, NumPy (информация будет обновляться).
Дополнительно будет осуществлена интеграция работы с Matlab. 

Также планируется создание системы API для работы с ПЛК (будет создан отдельный парсер 
для сбора информации с API сервиса и передачи на ПЛК).

# Что будет реализовано:

### Определение передаточой функции объекта по переходной кривой методом Симою ☑

Функции раздела:

- Возможность произвести идентификацию проекта по методу Симою. ☑
- Рассчёт передаточной функции Симою первого порядка. ☑
- Рассчёт передаточной функции Симою второго порядка. ☑
- Рассчёт передаточной функции Симою третьего порядка. ☑
- Вычисление коэффициента усиления. ☑

### Расчёт одноконтурной автоматической системы регилурования ☑

Функции раздела:

- Построения импульсной характеристики объекта. ☑
- Определения динамических параметров импульсной характеристики. ☑
- Перестройка импульсной характеристики в разгонную характеристику объекта. ☑
- Определенние параметров по разгонной характеристике (t, T1, T2, K). ☑
- Нахождение параметров T1, T2 методом Ольденбурга-Сарториуса. ☑
- Нахождение передаточной функции с помощью метода Симою.☑
- Построение переходных характеристик трёх моделей. ☑
- Определение значение дисперсии для трёх случаев (метод касательной, Ольденбурга-Сарториуса, Симою). ☑
- Получение наиболее идентичного переходного процесса при сравнении трёх случаев выше. ☑
- Построение плоскости параметров настройки ПИД-регулятора при подобранном C2. ☑
- Визуализирование переходного процесса с использованием регулятора. ☑
- Оценивание качества переходного процесса. ☑

### Получение приближенных математических моделей технологических объектов графоаналитическим методом ☑

Функции раздела:

- Построение передаточной фукнции объекта управления ☑
- Определение степени колебательности. ☑
- Вычисление параметров регулятора. ☑
- Построение графика D-разбиения параметров ПИ-регулятора. ☑
- Построение передаточной фукнции объекта управления с использованием ПИ-регулятора. ☑
- Определние степени затухания. ☑
- Оценивание качества (переходного процесса, степени затухания, длительности и т.д). ☑

### Расчёт комбинированной системы регулирования.

- Построение кривых разгона по каналу управления, возмущения
- Получение передаточных фукнций по каналам методом Симою
- Получение частотных характеристик объекта по каналу управления и возмущения
- Построение кривой равной степени колебательности
- Построение замкнутой системы ПИ-регулятора для нахождения интегрального квадратичного критерия качества
- Построение переходного процесса по управляющему воздействию, возмущающему
- Рассчёт показателей качества переходного процесса