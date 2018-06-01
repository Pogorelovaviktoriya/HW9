### Домашнее задание 9 (ДИЯ)

Заданияе заключалось в редактировани Повести временных лет.

Домашнее задание выполнялось с использованием регулярных выражений

**Удалить все пустые строки**

Command(Ctrl) + H (Replace All)

![](https://vk.com/away.php?utf=1&to=https%3A%2F%2Fgithub.com%2FPogorelovaviktoriya%2FHW9%2Fblob%2Fmaster%2Fscreen1.jpg)


Заменяем (^\n*\r*\s)|(^\n) на "" (Пустую строку) 

**Найти всех князей и города, имя и название которых оканчивается на "Слав"**

Command(Ctrl) + F (Find all)

(^|\s)+[А-Я][а-я]*(слав)

493 упоминания.

![](https://vk.com/away.php?utf=1&to=https%3A%2F%2Fgithub.com%2FPogorelovaviktoriya%2FHW9%2Fblob%2Fmaster%2Fscreen2.jpg)

**Найти все упоминания Новгорода**

Command(Ctrl) + F (Find all)

(^|\s)+[Н][а-я]*(город)

58 упоминаний.

![](https://vk.com/away.php?utf=1&to=https%3A%2F%2Fgithub.com%2FPogorelovaviktoriya%2FHW9%2Fblob%2Fmaster%2Fscreen3.jpg)

**После каждого знака препинания поставить пробел**

Command(Ctrl) + H (Replace All)

([.,:;-?!]) заменяем на \1 (Обязательно с пробелом в конце)

![](https://vk.com/away.php?utf=1&to=https%3A%2F%2Fgithub.com%2FPogorelovaviktoriya%2FHW9%2Fblob%2Fmaster%2Fscreen4.jpg)
