Программа-набор инструкций для компьютера,которые позволяют решить определенную задачу
Пакет(packege) представляет собой набор блоков кода,выполняющих похожие операции- например, форматирование строк или построение графических изображений.
Файлы Go почти всегда содержат одну или несколько директив import.
Каждый файл должен импортировать другие пакеты, чтобы использовать код ,содержащийся в этих пакетах.
В программе указываем только те пакеты, которые нам действительно нужны ,- то есть импортируем (import) эти пакеты.
ФУНКЦИЯ проедставляет собой набор строк кода , которые могут вызываться (выполняться) из других мест программы. 
При запуске прогрвмма Go ищет функцию  с именем main и выполняет ее в первую очередь ; поэтому - то мы присвоили своей функции имя main.
Программы Go должны соблюдать определленные правила, чтобы не сбивать с толку компилятор. Если вы нарушите одно из таких правил, компилятор выдаст сообщение об ошибке.
Чтобы вызвать функцию, введите имя функции (в данном случае Printin) и пару круглых скобок.
Как и многие , Println может получать один или несколько аргументов - значений, с которыми должна работать функция .Аргументы перечисляются в круглых скобках после имени функции.
Все аргументы, переданные этой функции, выводятся в терминале(а их значения разделяются пробелами ). после вывода всех аргументов Printin переходит на следующую строку в терминале.(ОТ сюда суффикс "in"- в сокращение от "line"- в конце имени.)
После того как пакет будет импортирован , вы сможете вызывать функции из этого пакета . Для этого укажите имя пакета, поставьте точку (.) и введите имя нужной функции.
Так как  мы собираемся импортировать несколько пакетов, который позволяет перечислять в круглых скобках сразу несколько пакетов, по одному имени пакета в строке.
При помощи операторов <и> можно сравнить два значения и проверить, какое 
После того как переменной будет присвоено значение,
