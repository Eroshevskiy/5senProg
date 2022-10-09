![image](https://user-images.githubusercontent.com/97594146/194746711-5fa21fa2-f2a1-4bcc-863e-a0e0a274e609.png)
![image](https://user-images.githubusercontent.com/97594146/194746724-5bf90e7d-8d3f-42ae-8c72-b5a3779206df.png)
![image](https://user-images.githubusercontent.com/97594146/194746734-b22cdaf7-efe4-468e-be29-82772a68c62e.png)
![image](https://user-images.githubusercontent.com/97594146/194746755-c1b5ea93-5626-4011-ab75-a065cebc9649.png)


Команды git при работе с командной строкой Основные понятия 1.Репозиторий - папка проекта. 2.Инлекс - файл, в которой содержится изменения, пдготовленные для добавления в коммит. 3.Коммит - фиксация изменений, внесенных в индекс. 4.Указатеели HEAD OrigHEAD и т. д. - это ссылка на определенный коммит. 5.Ветка - это последовательность коммитетов.

Bash и Git Bash Git Bash - командная оболочка которая позволяет работать с Git на прямую из коммандной строки.
![image](https://user-images.githubusercontent.com/97594146/194746772-5607fa40-ab73-4f69-9b28-158e04c785dd.png)
![image](https://user-images.githubusercontent.com/97594146/194746789-baaa63c5-acb3-4969-9c7e-401fef7315a5.png)
![image](https://user-images.githubusercontent.com/97594146/194746798-7a186792-0037-42a9-9926-fd0a326e0105.png)
![image](https://user-images.githubusercontent.com/97594146/194746813-da038253-4a97-4b0b-8277-0536328eaf4e.png)

Рабочая директория(Working Directory) Индекс/ Область подготовленных файлов Каталог Git image image image -l use a long listing format -l - выводить подробный список, в котором будет отображаться владелец, группа, дата создания, размер и другие параметры image

-a, --all do not ignore entries starting with . -a - отображать все файлы, включая скрытые, это те, перед именем которых стоит точка . - текущая папка .. - родительская папка d - directory

файл Права доступа : r - читать w - писать x - запускать от имени Администратора drwxr-xr-x Отделяют группы пользователей: rwx - одна группа(администратор/создать файла) r-x - вторая(пользователи файла)те, кто не авторизовался Initialized = создание
Перенос файлов с локального копьютера на сервере git init - создание репозитория
image 2. Перенос файла с сервера на локальный компьютер 


команда cat позволяет прочитать файлы 2022-09-07_10-43-27 (use "git rm --cached ..." to unstage) rm происходит от слова remove (удаление) - вместо него имя файла Readme.md


изображение

Команда git removed-привязывает к существующему репозиторию

персоональный токен git push https://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@github.com/Rubble2004/testtoken.git Скриншот_3
2022-09-09_10-35-48

