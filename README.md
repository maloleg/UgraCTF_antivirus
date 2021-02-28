# UgraCTF2020_antivirus

Посмотрим, какие пакеты мы отсылаем в бёрпе: <br />
Если выбрать тектовый файл  <br />
![alt text](https://github.com/maloleg/UgraCTF_antivirus/blob/master/1.png?raw=true) <br />
Если исполняемый <br />
![alt text](https://github.com/maloleg/UgraCTF_antivirus/blob/master/2.png?raw=true) <br />

заметим странный формат отправки типа, попробуем его поменять на рандомный: <br />
![alt text](https://github.com/maloleg/UgraCTF_antivirus/blob/master/3.png?raw=true) <br />

видимо отсылаемое название просто отсылается на сервер и там пытается исполнится соответственный питоновский скрипт. Также мы видим куда отсылаются наши файлы. <br />

Далее собственно вот пейлоад: <br />

![alt text](https://github.com/maloleg/UgraCTF_antivirus/blob/master/4.png?raw=true) <br />

И флаг находящийся в /etc/passwd: <br />

![alt text](https://github.com/maloleg/UgraCTF_antivirus/blob/master/6.png?raw=true) <br />

ugra_who_checks_the_checker_7dc3c0687ba6 <br />
