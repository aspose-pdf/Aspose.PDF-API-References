---
title: "Класс System::DateTimeOffset"
linktitle: "DateTimeOffset"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::DateTimeOffset. Содержит дату и время суток относительно всемирного координированного времени (UTC). Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1800
url: /ru/cpp/system/datetimeoffset/
---
## DateTimeOffset class


Содержит дату и время суток относительно всемирного координированного времени (UTC). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DateTimeOffset
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Добавляет указанный временной интервал к объекту [DateTimeOffset](./). |
| [AddDays](./adddays/)(double) const | Добавляет указанное количество дней к объекту [DateTimeOffset](./). |
| [AddHours](./addhours/)(double) const | Добавляет указанное количество часов к объекту [DateTimeOffset](./). |
| [AddMilliseconds](./addmilliseconds/)(double) const | Добавляет указанное количество миллисекунд к объекту [DateTimeOffset](./). |
| [AddMinutes](./addminutes/)(double) const | Добавляет указанное количество минут к объекту [DateTimeOffset](./). |
| [AddMonths](./addmonths/)(int) const | Добавляет указанное количество месяцев к объекту [DateTimeOffset](./). |
| [AddSeconds](./addseconds/)(double) const | Добавляет указанное количество секунд к объекту [DateTimeOffset](./). |
| [AddTicks](./addticks/)(int64_t) const | Добавляет указанное количество тиков к объекту [DateTimeOffset](./). |
| [AddYears](./addyears/)(int) const | Добавляет указанное количество лет к объекту [DateTimeOffset](./). |
| static [Compare](./compare/)(const DateTimeOffset\&, const DateTimeOffset\&) | Сравнивает два объекта [DateTimeOffset](./). |
| [CompareTo](./compareto/)(const DateTimeOffset\&) const | Сравнивает два объекта [DateTimeOffset](./). |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Сравнивает два объекта [DateTimeOffset](./). |
| [DateTimeOffset](./datetimeoffset/)() | Конструктор по умолчанию. |
| [DateTimeOffset](./datetimeoffset/)(DateTime) | Конструктор. |
| [DateTimeOffset](./datetimeoffset/)(int64_t, TimeSpan) | Конструктор. |
| [DateTimeOffset](./datetimeoffset/)(DateTime, TimeSpan) | Конструктор. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, TimeSpan) | Конструктор. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, TimeSpan) | Конструктор. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) | Конструктор. |
| static [Equals](./equals/)(const DateTimeOffset\&, const DateTimeOffset\&) | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени. |
| [Equals](./equals/)(const DateTimeOffset\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени. |
| [EqualsExact](./equalsexact/)(const DateTimeOffset\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени и имеют одинаковое смещение. |
| [EqualsExact](./equalsexact/)(const SharedPtr\<Object\>\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени и имеют одинаковое смещение. |
| static [FromFileTime](./fromfiletime/)(int64_t) | [Convert](../convert/)[Windows](../../system.windows/) время файла в дату и время с локальным смещением. |
| static [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(int64_t) | [Convert](../convert/) Unix-время в объект [DateTimeOffset](./). |
| static [FromUnixTimeSeconds](./fromunixtimeseconds/)(int64_t) | [Convert](../convert/) Unix-время в объект [DateTimeOffset](./). |
| [get_Date](./get_date/)() const | Получает компонент даты текущего объекта. |
| [get_DateTime](./get_datetime/)() const | Получает значение [DateTime](../datetime/). |
| [get_Day](./get_day/)() const | Получает день месяца текущего объекта. |
| [get_DayOfWeek](./get_dayofweek/)() const | Получает день недели текущего объекта. |
| [get_DayOfYear](./get_dayofyear/)() const | Получает день года текущего объекта. |
| [get_Hour](./get_hour/)() const | Получает компонент часа текущего объекта. |
| [get_LocalDateTime](./get_localdatetime/)() const | Получает значение [DateTime](../datetime/), представляющее локальную дату и время. |
| [get_Millisecond](./get_millisecond/)() const | Получает компонент миллисекунды текущего объекта. |
| [get_Minute](./get_minute/)() const | Получает компонент минуты текущего объекта. |
| [get_Month](./get_month/)() const | Получает компонент месяца текущего объекта. |
| static [get_Now](./get_now/)() | Получает [DateTimeOffset](./), у которого дата и время установлены на текущее локальное время, а смещение установлено в смещение локального времени. |
| [get_Offset](./get_offset/)() const | Получает смещение от UTC. |
| [get_Second](./get_second/)() const | Получает компонент секунды текущего объекта. |
| [get_Ticks](./get_ticks/)() const | Получает количество тиков текущего объекта. |
| [get_TimeOfDay](./get_timeofday/)() const | Получает время суток текущего объекта. |
| [get_UtcDateTime](./get_utcdatetime/)() const | Получает значение [DateTime](../datetime/), представляющее дату и время в UTC. |
| static [get_UtcNow](./get_utcnow/)() | Получает [DateTimeOffset](./), у которого дата и время установлены на текущее UTC-время, а смещение равно [TimeSpan::Zero](../timespan/zero/). |
| [get_UtcTicks](./get_utcticks/)() const | Получает количество тиков текущего объекта во времени UTC. |
| [get_Year](./get_year/)() const | Получает компонент года текущего объекта. |
| [GetHashCode](./gethashcode/)() const | Получает хеш-код для текущего объекта [DateTimeOffset](./). |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(const DateTimeOffset\&) const | Определяет, представляют ли текущий объект и указанный объект [DateTimeOffset](./) разные значения даты и времени. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Возвращает новый экземпляр класса [DateTimeOffset](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного интервала времени. |
| [operator-](./operator-/)(TimeSpan) const | Возвращает новый экземпляр класса [DateTimeOffset](./), представляющий значение даты и времени, полученное в результате вычитания указанного интервала времени из значения, представленного текущим объектом. |
| [operator-](./operator-/)(const DateTimeOffset\&) const | Возвращает экземпляр класса [TimeSpan](../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами. |
| [operator<](./operator_/)(const DateTimeOffset\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое ранее, чем значение, представленное указанным объектом [DateTimeOffset](./). |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(const DateTimeOffset\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое ранее или равно значению, представленному указанным объектом [DateTimeOffset](./). |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator==](./operator==/)(const DateTimeOffset\&) const | Определяет, представляют ли текущий объект и указанный объект [DateTimeOffset](./) одинаковое значение даты и времени. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(const DateTimeOffset\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое позже, чем значение, представленное указанным объектом [DateTimeOffset](./). |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(const DateTimeOffset\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое позже или равно значению, представленному указанным объектом [DateTimeOffset](./). |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Преобразует указанную строку в эквивалент [DateTimeOffset](./). |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Преобразует указанную строку в объект [DateTimeOffset](./), используя указанный поставщик формата и стиль форматирования. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Преобразует указанную строку в объект [DateTimeOffset](./), используя указанный формат, поставщик формата и стиль форматирования. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Преобразует указанную строку в объект [DateTimeOffset](./), используя указанные форматы, поставщик формата и стиль форматирования. |
| [Subtract](./subtract/)(TimeSpan) const | Вычитает указанный интервал времени из текущего объекта. |
| [Subtract](./subtract/)(const DateTimeOffset\&) const | Вычитает указанное значение [DateTimeOffset](./) из текущего объекта. |
| [ToFileTime](./tofiletime/)() const | Преобразует текущий объект во время файла [Windows](../../system.windows/). |
| [ToLocalTime](./tolocaltime/)() const | Преобразует текущий объект в объект, представляющий локальное время. |
| [ToOffset](./tooffset/)(TimeSpan) const | Заменяет смещение текущего объекта указанным смещением. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Преобразует текущий объект в строку, используя указанный формат и поставщик формата. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Преобразует текущий объект в строку, используя указанный поставщик формата. |
| [ToString](./tostring/)(const String\&) const | Преобразует текущий объект в строку, используя указанный формат. |
| [ToString](./tostring/)() const | Преобразует текущий объект в строку. |
| [ToUniversalTime](./touniversaltime/)() const | Преобразует текущий объект в объект, представляющий время UTC. |
| [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Получает количество миллисекунд, прошедших с начала эпохи Unix. |
| [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Получает количество секунд, прошедших с начала эпохи Unix. |
| static [TryParse](./tryparse/)(const String\&, DateTimeOffset\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./). |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./), используя указанный поставщик формата и стиль форматирования. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./), используя указанные форматы, поставщик формата и стиль форматирования. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./), используя указанный формат, поставщик формата и стиль форматирования. |
| static [Type](./type/)() | Возвращает объект [TypeInfo](../typeinfo/), представляющий структуру [TimeSpan](../timespan/). |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Получает максимальное смещение в тиках. |
| static [MaxValue](./maxvalue/) | Получает наибольшее значение [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Получает минимальное смещение в тиках. |
| static [MinValue](./minvalue/) | Получает самое раннее значение [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | Получает начало эпохи Unix. |
## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
