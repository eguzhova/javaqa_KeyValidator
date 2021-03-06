### Отчёт о тестировании KeyValidator

#### Краткое описание
4 апреля 2021 было проведено тестирование документации и установки приложения по проверке лицензионных ключей KeyValidator

**На тестирование затрачено:** 2 часа

В результате тестирования выявлены следующие дефекты:
* [Ключи для проверки в руководстве по использованию указаны не верно](https://github.com/eguzhova/javaqa_KeyValidator/issues/1)

#### Описание процесса тестирования
В процессе тестирования использовался тестовый сценарий:

1. Установить OpenJDK 11 
1. Запустить проверку валидных и не валидных ключей из руководства по использованию KeyValidator
1. Оценить правильность результата

**Тестовые данные:**
1. [Руководство по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
1. [Руководство использования KeyValidator](https://github.com/eguzhova/javaqa_KeyValidator/blob/master/user_manual.md)

#### Тестирование производилось в следующем окружении:
* MacOS 11.2.3 (20D91)
* openjdk version "11.0.10" 2021-01-19