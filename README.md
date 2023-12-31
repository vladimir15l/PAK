## Симулятор несжимаемой жидкости

![alt text](https://github.com/Spektoruk3/PAK/blob/main/image/git.jpg)
# Описание
Симулятор несжимаемой жидкости, основанный на уравнениях Навье-Стокса и реализованный с помощью языка Python.
<br>

----------------------------------------------------------------

## Запуск приложения
<br>

> Для установки приложения Вам необходимо создать любую папку
> Открыть эту папку через любой компилятор, например, VS Code
> Создать новый терминал и ввести последовательно команды:
  1) python -m venv env
  3) cd ./env/Scripts
  4) ./activate.bat
  5) pip install FluidCubeGame
  6) Затем в этой же папке создать любой файл *.py с следющим содержанием:
     
     from src.FluidCubeGame.main import main

     main()
  8) Запустить программу

### Docker-образ
> Ссылка на скачивание - https://hub.docker.com/r/megasear/fluidcube
>
> Для самостоятельной сборки Docker образа можно использовать Dockerfile.
> 
> $ docker build . -t fluidSimulator

----------------------------------------------------------------

## Используемые библиотеки
> - numpy - это основной пакет для научных вычислений с помощью Python.<br>
> - pygame - графический интерфейс GUI для взаимодействия пользователя с программой
> - sys - предоставляет доступ к системным функциям (например sys.exit())

----------------------------------------------------------------

## Список разработчиков
> - Лёшин Владимир
> - Круковский Василий
> - Спекторук Илья
<br>

----------------------------------------------------------------

## Инструкции по отправке сообщений об ошибках
> В случае получения ошибок программы просьба сообщить на почту v.leshin@g.nsu.ru с описанием ошибки и скриншотами приложения. 
<br>
