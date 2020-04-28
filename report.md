# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

25.04.2020 - 26.04.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
1. Карта Visa:
4916739148237048812 FAIL ожидание OK
2. Card Diners Club
36327423783856 FAIL ожидание OK
3. Card American Express
379812791854459 FAIL ожидание ОК
4. Card JCB
3537853465522596684 FAIL ожидание OK
5. Card Discover
6011989062914874264 FAIL ожидание OK

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Main.class

В качестве тестовых данных использовались данные `https://www.freeformatter.com/credit-card-number-generator-validator.html`

# Visa
* 4716850338845394 ok
* 4716308203839828 ok
* 4916739148237048812 ok

# MasterCard
* 5588380721166457 ok
* 5358801077563961 ok

# Maestro
* 5018535859706362 ok
* 5038382011924419 ok

# Visa Electron
* 4026531677779189 ok

# Diners Club - International
* 36327423783856 ok

# American Express
* 379812791854459 ok

# JCB
* 3537853465522596684 ok
* 3530863435023753 ok

# Discover
* 6011505488652407
* 6011989062914874264


Тестирование производилось в следующем окружении:
* Windows 8 x64
* openjdk version "11.0.7" 2020-04-14
* IDE Community 2020.1