### Домашнее задание 9 (ДИЯ)

Задание заключалось в редактировании Повести временных лет.

Домашнее задание выполнялось с использованием регулярных выражений

**Удалить все пустые строки**

Command(Ctrl) + H (Replace All)

![](https://github.com/Pogorelovaviktoriya/HW9/blob/master/screen1.jpg)


Заменяем (^\n*\r*\s)|(^\n) на "" (Пустую строку) 

**Найти всех князей и города, имя и название которых оканчивается на "Слав"**

Command(Ctrl) + F (Find all)

(^|\s)+[А-Я][а-я]*(слав)

493 упоминания.

![](https://github.com/Pogorelovaviktoriya/HW9/blob/master/screen2.jpg)

**Найти все упоминания Новгорода**

Command(Ctrl) + F (Find all)

(^|\s)+[Н][а-я]*(город)

58 упоминаний.

![](https://github.com/Pogorelovaviktoriya/HW9/blob/master/screen3.jpg)

**После каждого знака препинания поставить пробел**

Command(Ctrl) + H (Replace All)

([.,:;-?!]) заменяем на \1 (Обязательно с пробелом в конце)

![](https://github.com/Pogorelovaviktoriya/HW9/blob/master/screen4.jpg)
