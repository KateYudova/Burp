1) Переходим по адресу /web-client/ch4/ch4.html
2) Пытаемся ввести пароль, но ничего не получается
![](L1E92GkfUOU.jpg)
![](I1GB2blmoWQ.jpg)
3) Открываем код страницы, находим скрипт и пытаемся понять, что же нам нужно
![](JOZG3VCOv_g.jpg)
4) Строку pass надо раскодировать как URL, т.к. там есть метод unescape() и получаем "cpasbiendurpassword"
![](eYi0fQfB3vE.jpg)
