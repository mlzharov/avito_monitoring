Avito Monitoring
==================
   Это простой скрипт для мониторинга новых объявлений на сайте [avito.ru][2]. Следит за появлением новых объявлений (не учитывая рекламы и пр.), отбирает информацию о них (описание, стоимость и место) и отправляет на указанную почту. Лично мне, он очень сильно помог при поиске комнаты.
   В общем случае, необходимо запустить скрипт, он создаст YAML-файл с настройками, после нужно указать в нем url со страницей с нужными параметрами и товарами и изменить настройки для отправки почтовых уведомлений, такие как 'sender','server' и т.д.
   Скрипт не особо умный, посему, при изменении верстки на сайте, может легко крэшиться. Так что следите за тем, что он получает и в каком виде.
   Написан на Ruby, используется гем [Pony][1]. Удачи)

[1]: https://github.com/benprew/pony  "Pony"
[2]: http://www.avito.ru/             "avito.ru"