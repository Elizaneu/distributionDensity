# Distribution Density
Проект "Плотность распределения" в рамках дисциплины "Введение в пакеты научных и инженерных вычислений"

1. Функция generate_data генерирует выборки размерности 1000.
2. Функция scatter_histogram строит диаграмму рассеяния и гистограмму.
3. Функция kde вычисляет ядерную оценку плотности (Kernel density estimation).
4. Функция update обновляет данные на основе величины на ползунке. В качестве изменяемой величины была выбрана пропускная способность (bandwidth).
5. Функция on_button_clear_clicked очищает график при нажатии на соответствующую кнопку.
6. Функция optimal_estimate вычисляет значение bandwidth, которое максимизирует логарифмическую вероятность данных, и на основе параметра строит график.

Update:
1. Функция kde_manual_calc вычисляет KDE с помощью формулы.
2. Функция update_manual обновляется данные, используя kde_manual_calc.
