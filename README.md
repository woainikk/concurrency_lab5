Необходимо разложить натуральное число типа uint64_t на простые множители.

Программа открывает текстовый файл и последовательно считывает из файла числа, для которых и вычисляет разложение, складывая результат в выходной файл 

Все вычисления происходят в отдельном потоке. 
Во время работы, если ввести с клавиатуры слово exit, то программа ожидает окончания расчета одного (текущего) разложения, затем закрывает выходной и входной файлы и корректно завершает работу.

Если ввести слово pause, то программа приостанавливает работу и закрывает выходной файл. После чего, если ввести resume, то она продолжает свою работу (выходной файл при этом не перезаписывает, а начинает дополнять).

Оптимизировать скорость вычислений, задействуя несколько вычислительных потоков (количество потоков задается пользователем из командной строки: 1, 2, 3, ..). 
