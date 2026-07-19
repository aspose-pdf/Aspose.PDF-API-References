---
title: "Класс System::TimeZoneInfo::AdjustmentRule"
linktitle: "AdjustmentRule"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::TimeZoneInfo::AdjustmentRule. Предоставляет информацию о корректировке часового пояса. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3300
url: /ru/cpp/system/timezoneinfo/adjustmentrule/
---
## AdjustmentRule class


Предоставляет информацию о корректировке часового пояса. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AdjustmentRule : public System::IEquatable<AdjustmentRulePtr>
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) | Создаёт экземпляр класса [AdjustmentRule](./), представляющего правило корректировки времени, описанное заданными параметрами. |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) | Создаёт экземпляр класса [AdjustmentRule](./), представляющего правило корректировки времени, описанное заданными параметрами. |
| [Equals](./equals/)(AdjustmentRulePtr) override |  |
| [get_BaseUtcOffsetDelta](./get_baseutcoffsetdelta/)() const | Возвращает дельту от стандартного смещения UTC. |
| [get_DateEnd](./get_dateend/)() const | Возвращает объект [DateTime](../../datetime/), представляющий дату и время, когда правило корректировки перестаёт действовать. |
| [get_DateStart](./get_datestart/)() const | Возвращает объект [DateTime](../../datetime/), представляющий дату и время, когда правило корректировки вступает в силу. |
| [get_DaylightDelta](./get_daylightdelta/)() const | Возвращает объект [TimeSpan](../../timespan/), представляющий количество времени, необходимое для формирования перехода на летнее время в часовом поясе. |
| [get_DaylightTransitionEnd](./get_daylighttransitionend/)() const | Возвращает информацию о переходе от стандартного времени к летнему времени. |
| [get_DaylightTransitionStart](./get_daylighttransitionstart/)() const | Возвращает информацию о переходе от летнего времени к стандартному времени. |
| [get_HasDaylightSaving](./get_hasdaylightsaving/)() const | ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../object/gethashcode/). Позволяет выполнять хеширование пользовательских объектов. |
## См. также

* Class [IEquatable](../../iequatable/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
