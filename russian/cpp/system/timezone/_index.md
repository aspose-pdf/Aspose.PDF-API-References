---
title: "Класс System::TimeZone"
linktitle: "TimeZone"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::TimeZone. Представляет часовой пояс. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 6500
url: /ru/cpp/system/timezone/
---
## TimeZone class


Представляет часовой пояс. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TimeZone : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [get_CurrentTimeZone](./get_currenttimezone/)() | Возвращает новый экземпляр класса [TimeZone](./), представляющий текущий часовой пояс. |
| virtual [get_DaylightName](./get_daylightname/)() const | Возвращает название летнего времени часового пояса, представленного текущим объектом. |
| virtual [get_StandardName](./get_standardname/)() const | Возвращает название стандартного времени часового пояса, представленного текущим объектом. |
| virtual [GetDaylightChanges](./getdaylightchanges/)(int32_t) | Возвращает период летнего времени для конкретного года. |
| virtual [GetUtcOffset](./getutcoffset/)(DateTime) | Возвращает смещение UTC для указанного местного времени. |
| virtual [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) | Определяет, попадает ли значение даты и времени, представленное указанным объектом [DateTime](../datetime/), в диапазон летнего времени для часового пояса, представленного текущим объектом [TimeZone](./). |
## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
