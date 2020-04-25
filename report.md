# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

25.04.2020 - 26.04.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* KeyValidator 80b427f8-92cd-3aae-ba04-3927fbe17c6 FAIL ожидание ok
* KeyValidator 387eedc6-12e9-3b32-9881-63b6b5e85317 FAIL ожидание ok
* KeyValidator 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 ok ожидание FAIL

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Main.class

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html

# Visa
* 4716850338845394 ok
* 4716308203839828 ok

# MasterCard
* 5588380721166457 ok
* 5358801077563961 ok

# Maestro
* 5018535859706362 ok
* 5038382011924419 ok

# Visa Electron
* 4026531677779189 ok


Тестирование производилось в следующем окружении:
* Windows 8 x64
* openjdk version "11.0.7" 2020-04-14
* IDE Community 2020.1