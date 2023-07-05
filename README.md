# Модуль фитнес-трекера
Модуль фитнес-трекера выводит информационное сообщение о результатах тренировки.

## Описание проекта:
Модуль фитнес-трекера, использует парадигму ООП. Модуль определяет данные
для трёх видов тренировок: бега, спортивной ходьбы и плавания. Рассчитывает и
отображает результаты тренировки.

Модуль фитнес-трекера выполняет следующие функции:
* принимает от блока датчиков информацию о прошедшей тренировке;
* определяет вид тренировки;
* рассчитывает результаты тренировки;
* выводит информационное сообщение о результатах тренировки.  

Информационное сообщение включает такие данные:
* тип тренировки (бег, ходьба или плавание);
* длительность тренировки;
* дистанция, которую преодолел пользователь, в километрах;
* среднюю скорость на дистанции, в км/ч;
* расход энергии, в килокалориях.

## Стек технологий:

* [Python 3.7+](https://www.python.org/downloads/)

## Как запустить проект:

* Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Olga07122007/hw_python_oop.git
```

```
cd hw_python_oop
```

* Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
venv/scripts/activate
```

* Установить зависимости из файла ```requirements.txt```:

```
pip install -r requirements.txt
```

* Запустить трекер:
```
python homework.py
```
