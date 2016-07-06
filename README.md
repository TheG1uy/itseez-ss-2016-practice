# Летняя межвузовская школа, 2016 год


[![Feedback](./docs/feedback.png)][feedback_form]

[![Join the chat at https://gitter.im/itseez-academy/itseez-ss-2016-practice](https://badges.gitter.im/itseez-academy/itseez-ss-2016-practice.svg)](https://gitter.im/itseez-academy/itseez-ss-2016-practice?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## Практикум

Практикум предполагает выполнение четырех лабораторных работ, которые
направлены на освоение материала, представленного на лекциях. Первая работа 
полностью техническая, цель - получение навыков работы с такими инструментами
разработки программного обеспечения, как система контроля Git, CMake и
Google Testing Framework. Вторая работа позволяет познакомить слушателей
с основами работы с библиотекой OpenCV, в частности, с базовыми примитивами
работы с изображениями/видео и функциями их обработки, содержащимися в модулях
core, imgproc и highgui. Цель третьей и четвертой работ состоит в том, чтобы
попробовать решить классические задачи компьютерного зрения (детектирование
и сопровождение объектов) с использованием имеющегося функционала библиотеки
OpenCV. Каждая работа предполагает реализацию некоторого программного модуля
и приложения, демонстрирующего разработанный функционал.

## Структура репозитория

Репозиторий содержит следующие директории и файлы:

  - `3rdparty\gtest` - директория, содержащая библиотеку Google Testing Framework.
  - `docs` - директория, содержащая описание практических заданий, и вспомогательные изображения.
  - `include` - заголовочные файлы модулей библиотеки `summer_school_2016_lib`,
    разрабатываемых в ходе выполнения каждой работы.
  - `samples` - примеры использования разработанных методов. Изначально директория
    содержит шаблонный пример консольного приложения `template_demo.cpp`.
    Каждая практика предполагает разработку собственного приложения,
    обеспечивающего решение соответствующей задачи, на базе указанного шаблона.
  - `src` - исходные файлы модулей библиотеки `summer_school_2016_lib`.
  - `test` - исходные файлы тестов.
  - `CMakeLists.txt` - общий файл для сборки проектов с помощью CMake.
  - `README.md` - данный файл.
  - `.gitignore`- перечень директорий/файлов, которые игнорируются системой контроля версий.

## Инструкции

Описание практических заданий можно найти в следующих документах:

  1. [Практика 1. Инструменты разработки ПО](docs/README_1.md).
  1. [Практика 2. Основы работы с библиотекой OpenCV. Модули core, imgproc и highgui](docs/README_2.md).
  1. [Практика 3. Детектирование объектов с использованием каскадного классификатора](docs/README_3.md).
  1. [Практика 4. Сопровождение объектов с использованием алгоритма Median Flow](docs/README_4.md).

По завершении изучения лекционных материалов пятого рабочего дня Летней школы
заполниите, пожалуйста, [отзыв участника][feedback_day5].

<!-- LINKS -->
[feedback_form]: https://docs.google.com/forms/d/1tkVTza1_0zxO013ukRquIaODo2MirhCmWvLOIINFkxc/viewform
[feedback_day5]: https://docs.google.com/forms/d/1F0VMvP67dYnOGTzMuWlZROZ5FODjw9zKmJUCIATEoy8/viewform
