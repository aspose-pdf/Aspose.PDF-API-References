---
title: "System::Timers::Timer класс"
linktitle: "Timer"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Timers::Timer класс. Таймер, который вызывает делегат в цикле в C++."
type: docs
weight: 200
url: /ru/cpp/system.timers/timer/
---
## Timer class


[Timer](./) that calls delegate in a loop.

```cpp
class Timer : public System::ComponentModel::Component
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() | Останавливает таймер, освобождает выделенные ресурсы. |
| [Dispose](./dispose/)() | Останавливает таймер, освобождает выделенные ресурсы. |
| [get_AutoReset](./get_autoreset/)() const | Проверяет, находится ли таймер в режиме автоматического сброса. |
| [get_Enabled](./get_enabled/)() const | Проверяет, активен ли таймер. |
| [get_Interval](./get_interval/)() const | Получает интервал таймера. |
| [get_IsStopped](./get_isstopped/)() const | Проверяет, остановлен ли таймер. |
| [set_AutoReset](./set_autoreset/)(bool) | Устанавливает таймер в режим автоматического сброса или выключает его. |
| [set_Enabled](./set_enabled/)(bool) | Запускает или останавливает таймер. Запуск таймера не перезапускает отсчёт времени, если таймер уже работает. |
| [set_Interval](./set_interval/)(double) | Устанавливает интервал таймера. |
| [Start](./start/)() | Запускает таймер. Не перезапускает отсчёт времени, если таймер уже работает. |
| [Stop](./stop/)() | Останавливает таймер. |
| [Timer](./timer/)() | Информация RTTI. |
| [Timer](./timer/)(double) | Создаёт остановленный таймер с указанным интервалом. |
## См. также

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Timers](../)
* Library [Aspose.PDF for C++](../../)
