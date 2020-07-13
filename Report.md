# Отчёт о тестировании Card's validator

## Краткое описание

 12/07/2020 - 12/07/2020 было проведено <функциональное тестирование,тестирование совместимости > функциональности валидации номера банковской карты.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты: 
* Not valid standart 19 digits Visa card   <https://github.com/alicenetologia/java_leccion1_task2/issues/1>
* Valid 16 digit Master card  <https://github.com/alicenetologia/java_leccion1_task2/issues/2>
* Not valid 15 digit American Express card  <https://github.com/alicenetologia/java_leccion1_task2/issues/3>
* Not valid 13 digit Visa card  <https://github.com/alicenetologia/java_leccion1_task2/issues/4>


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:

* Bug Github Issue report


В качестве тестовых данных использовались данные:
* Valid number card has 16 digits


Тестирование производилось в следующем окружении:
* Mac OS 64
* Java 11.0.5


