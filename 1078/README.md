1078. Отрезки
Ограничение времени: 1.0 секунды
Ограничение памяти: 64 МБ

Несколько отрезков лежат на прямой. Каждый отрезок задан координатами его концов. Отрезки занумерованы от 1 до N (0 < N < 500). Будем считать, что отрезок лежит внутри другого, если два отрезка различны, первый полностью содержится во втором и их концы не совпадают. Напишите программу, которая находит количество отрезков в самой длинной последовательности вложенных отрезков. В последовательности каждый отрезок, кроме последнего, должен находиться внутри следующего отрезка последовательности.

Исходные данные

Первая строка содержит одно целое число N. Затем следуют N строк, в каждой содержатся два целых числа, которые являются координатами левого и правого концов соответствующего отрезка. Эти координаты — целые в диапазоне [–10000, 10000]. Отрезки нумеруются в соответствии с их местом во входных данных.

Результат

Первая строка должна содержать одно целое число — количество отрезков в найденной последовательности. Следующая строка должна содержать номера отрезков, составляющих эту последовательность. Эти номера должны быть выведены в порядке увеличения длин отрезков. Если существует более одной искомой последовательности, выведите любую из них.
