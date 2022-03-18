# Classwork. C++ basics

[![Build Status](../../actions/workflows/cmake.yml/badge.svg)](../../actions/workflows/cmake.yml)

## Описание

Модули:
1. Структура программы: функция _main_, входные аргументы.
2. Базовые примитивные типы данных: объявление и инициализация переменных.
3. Базовые операторы: арифметические, сравнения, логические, побитывые.
4. Оператор ветвления _if-else_.
5. Циклы _for_ и _while_. Операторы _break_ и _continue_.
6. Функции: объявление и определение, входные параметры, возвращаемое значение.
7. Стандартные потоки ввода и вывода _iostream_. Форматированный вывод _printf_.
8. Указатели: память и адреса, доступ к данным по указателю, нулевой указатель.
9. Статические массивы: объявление и инициализация, связь с указателями, копирование.
10. Ссылки: разница между ссылкой и указателем.
11. Функции: передача аргументов по значению, указателю и ссылке. Передача массивов.
12. Базовые принципы управления памятью: понятие области видимости, стек и куча, операторы _new_ и _delete_.
13. Динамические массивы: операторы _new[]_ и _delete[]_, изменение длины массива.
14. Разделение программы на исходный код и заголовочные файлы. Объявление и определение функций.
15. Структуры: приватные и публичные поля и методы, констуктор и деструктор.

Структура проекта:
- [_src_](src) - исходный код программ;
- [_include_](include) - заголовочные файлы;
- [_.github_](.github) - конфигурационные файлы запуска автоматической сборки проекта (CI);
- [_cmake_](cmake) - файлы конфигурации средства сборки проектов CMake;
- [_CMakeLists.txt_](CMakeLists.txt) - главный файл конфигурации средства сборки CMake;
- _.clang-*_ - конфигурации линтера и форматирования кода в среде разработки. 

## Как запустить?

Склонируйте/импортируйте репозиторий при помощи среды разработки или вручную через терминал:
```shell
git clone https://github.com/Algorithms-and-Data-Structures-2022/cpp-basics-classwork.git
```

Сборка и запуск проекта осуществляются через среду разработки. 
