---
title: "Класс System::TimeSpan"
linktitle: "TimeSpan"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::TimeSpan. Представляет интервал времени. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 6400
url: /ru/cpp/system/timespan/
---
## TimeSpan class


Представляет интервал времени. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class TimeSpan
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, который является суммой интервалов, представленных текущим и указанным объектами. |
| static [Compare](./compare/)(TimeSpan, TimeSpan) | Сравнивает два объекта [TimeSpan](./). |
| [CompareTo](./compareto/)(TimeSpan) const | Сравнивает текущий и указанный объекты. |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Сравнивает текущий и указанный объекты. |
| [Duration](./duration/)() const | Возвращает новый экземпляр объекта [TimeSpan](./), значение которого является абсолютным значением текущего объекта. |
| [Equals](./equals/)(TimeSpan) const | Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| static [Equals](./equals/)(TimeSpan, TimeSpan) | Возвращает true, если указанные объекты представляют один и тот же интервал времени, иначе — false. |
| static [FromDays](./fromdays/)(double) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [FromHours](./fromhours/)(double) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [FromMilliseconds](./frommilliseconds/)(double) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [FromMinutes](./fromminutes/)(double) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [FromSeconds](./fromseconds/)(double) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [FromTicks](./fromticks/)(int64_t) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| [get_Days](./get_days/)() const | Возвращает компонент дней интервала времени, представленного текущим объектом [TimeSpan](./). |
| [get_Hours](./get_hours/)() const | Возвращает компонент часов интервала времени, представленного текущим объектом [TimeSpan](./). |
| [get_Milliseconds](./get_milliseconds/)() const | Возвращает компонент миллисекунд интервала времени, представленного текущим объектом [TimeSpan](./). |
| [get_Minutes](./get_minutes/)() const | Возвращает компонент минут интервала времени, представленного текущим объектом [TimeSpan](./). |
| [get_Seconds](./get_seconds/)() const | Возвращает компонент секунд интервала времени, представленного текущим объектом [TimeSpan](./). |
| [get_Ticks](./get_ticks/)() const | Возвращает количество интервалов по 100 наносекунд, составляющих интервал времени, представленный текущим объектом [TimeSpan](./). |
| [get_TotalDays](./get_totaldays/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных днях. |
| [get_TotalHours](./get_totalhours/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных часах. |
| [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных миллисекундах. |
| [get_TotalMinutes](./get_totalminutes/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных минутах. |
| [get_TotalSeconds](./get_totalseconds/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных секундах. |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код для текущего объекта. |
| [IsNull](./isnull/)() const |  |
| [Negate](./negate/)() const | Возвращает новый экземпляр объекта [TimeSpan](./), представляющий отрицательное значение текущего объекта [TimeSpan](./). |
| [operator!=](./operator!=/)(TimeSpan) const | Определяет, не равен ли интервал времени, представленный текущим объектом, интервалу времени, представленному указанным объектом. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, который является суммой интервалов, представленных текущим и указанным объектами. |
| [operator+](./operator+/)() const | Возвращает себя. |
| [operator+=](./operator+=/)(TimeSpan) | Присваивает текущему объекту интервал времени, который является суммой интервалов, представленных текущим и указанным объектами. |
| [operator-](./operator-/)(TimeSpan) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, который является результатом вычитания интервала времени, представленного указанным объектом, из интервала времени, представленного текущим объектом. |
| [operator-](./operator-/)() const | Возвращает новый экземпляр объекта [TimeSpan](./), представляющий отрицательное значение текущего объекта [TimeSpan](./). |
| [operator-=](./operator-=/)(TimeSpan) | Назначает текущему объекту интервал времени, который является результатом вычитания интервала времени, представленного указанным объектом, из интервала времени, представленного текущим объектом. |
| [operator/](./operator//)(double) const |  |
| [operator/](./operator//)(TimeSpan) const |  |
| [operator/=](./operator/=/)(double) |  |
| [operator<](./operator_/)(TimeSpan) const | Определяет, короче ли интервал времени, представленный текущим объектом, чем интервал времени, представленный указанным объектом. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(TimeSpan) const | Определяет, короче ли или равен интервал времени, представленный текущим объектом, интервалу времени, представленному указанным объектом. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const TimeSpan\&) | Устанавливает интервал времени, представленный указанным объектом [TimeSpan](./), в текущий объект [TimeSpan](./). |
| [operator==](./operator==/)(TimeSpan) const | Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(TimeSpan) const | Определяет, длиннее ли интервал времени, представленный текущим объектом, чем интервал времени, представленный указанным объектом. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(TimeSpan) const | Определяет, длиннее ли или равен интервал времени, представленный текущим объектом, интервалу времени, представленному указанным объектом. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Преобразует строку в эквивалентный объект [TimeSpan](./). |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанный поставщик формата. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанные форматы, поставщик формата и стили. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанный формат, поставщик формата и стили. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| [Subtract](./subtract/)(TimeSpan) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, который является результатом вычитания интервала времени, представленного указанным объектом, из интервала времени, представленного текущим объектом. |
| [TimeSpan](./timespan/)() | Создаёт объект [TimeSpan](./), представляющий нулевой интервал времени. |
| explicit [TimeSpan](./timespan/)(int64_t) | Создаёт экземпляр класса [TimeSpan](./), представляющий указанный интервал времени. |
| [TimeSpan](./timespan/)(int, int, int) | Создаёт экземпляр класса [TimeSpan](./), представляющий интервал времени, равный сумме указанного количества часов, минут и секунд. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Создаёт экземпляр класса [TimeSpan](./), представляющий интервал времени, равный сумме указанного количества часов, минут, секунд и миллисекунд. |
| [TimeSpan](./timespan/)(const TimeSpan\&) | Создаёт объект [TimeSpan](./), представляющий интервал времени, равный интервалу времени, представленному указанным объектом [TimeSpan](./). |
| [ToString](./tostring/)() const | Возвращает строковое представление интервала времени, представленного текущим объектом. |
| [ToString](./tostring/)(const String\&) const | Преобразует значение текущего объекта в эквивалентное строковое представление, используя указанный формат. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Преобразует значение текущего объекта в эквивалентное строковое представление, используя указанный формат и поставщик формата. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| static [TryParse](./tryparse/)(const String\&, TimeSpan\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) и возвращает результат преобразования. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанный поставщик формата, и возвращает результат преобразования. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанные форматы и поставщик формата, и возвращает результат преобразования. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанный формат, поставщик формата и стили, и возвращает результат преобразования. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанные форматы, поставщик формата и стили, и возвращает результат преобразования. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Преобразует строку в эквивалентный объект [TimeSpan](./), используя указанный формат и поставщик формата, и возвращает результат преобразования. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [Type](./type/)() | Возвращает объект [TypeInfo](../typeinfo/), представляющий структуру [TimeSpan](./). |
## Поля

| Поле | Описание |
| --- | --- |
| static [MaxValue](./maxvalue/) | Объект [TimeSpan](./), представляющий самый длинный возможный интервал. |
| static [MinValue](./minvalue/) | /// Объект [TimeSpan](./), представляющий самый короткий возможный интервал. |
| static constexpr [TicksPerDay](./ticksperday/) | Количество интервалов по 100 наносекунд в дне (24-часовой интервал). |
| static constexpr [TicksPerHour](./ticksperhour/) | Количество интервалов по 100 наносекунд в часе. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Количество интервалов по 100 наносекунд в миллисекунде. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Количество интервалов по 100 наносекунд в минуте. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Количество интервалов по 100 наносекунд в секунде. |
| static [Zero](./zero/) | Объект [TimeSpan](./), представляющий нулевой интервал. |
## Примечания



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
