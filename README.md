# Лабораторная работа №6 Система контроля версий
### Цель работы
Изучение базовых возможностей системы управленияя версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

### Ход работы
1. Создаем аккаунт на сайте GitHub и создаем копию репозитория лабораторной работы в личное хранилище. Для этого надо перейти в репозиторий с лабораторнй работой и нажать на кнопку "fork". 
   - [Ccылка на аккаунт](https://github.com/VyborovAndrey) 
      <p align="center">
         <img src="screenshots/0.png">
         Рисунок 1 - Аккаунт GitHub и созданный fork репозитория
      </p>
2. Устанавливаем Git.
   - Для того чтобы установить Git необходимо перейти на официальный сайт Git и оттуда скачать клиент Git совместимый с нашей операционной системой.
      <p align="center">
         <img src="screenshots/1.png"><br>
         Рисунок 2 - Версия установленного Git
      </p>
3. Настраиваем клиент Git
    - Для того чтобынатсроить клиент Git необходимо выполнить следующие действия:
      - Выполнить команду `git config --global user.name имя_пользователя` для установки имени пользователя.
      - Выполнить команду `git config --global user.email email_пользователя` для установки email пользователя.
         <p align="center">
            <img src="Screenshots/2.png"><br>
            Рисунок 3 - Настройка клиента Git
         </p>
4. Создаем локальную копию удаленного репозитория
   - Для того чтобы клонировать репозиторий к себе на компьютер необходимо выполнить следующие действия:
     - Перейти в желаемое место расположения репозитория с помощью команды `cd название_папки`.
     - С помощью команды `git clone адрес_репозтория` скопировать репозиторий.
      <p align="center">
         <img src="Screenshots/3.png"><br>
         Рисунок 4 - Создание локальной копии удаленного репозитория
      </p>
5.  Добавляем тестовый файл через интерфейс GitHub
    - Для того чтобы добавить тестовый файл в наш репозиторий переходим на страницу нашего репозитория на сайте GitHub. После этого нажимаем на кнопку "Add file". В окне создания файла даем ему название "TestGitFile", заполняем его информацией и подтверждаем его создание. После подтверждения создания файла автоматически содается коммит "Create TestGitFile".
      <p align="center">
         <img src="Screenshots/4.png"><br>
         Рисунок 5 - Созданный файл через интерфейс GitHub
      </p>
6. Добовление созданного файла в локальный репозиторий
   - Для подтягивания созданного файла используется команда `git pull`
      <p align="center">
         <img src="Screenshots/5.png"><br>
         Рисунок 5 - Подтягивание файла с помощью git pull
      </p>