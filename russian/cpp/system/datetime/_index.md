---
title: "System::DateTime класс"
linktitle: "DateTime"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DateTime класс. Представляет конкретное значение даты и времени на временной шкале. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 1700
url: /ru/cpp/system/datetime/
---
## DateTime class


Представляет конкретное значение даты и времени на временной шкале. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class DateTime
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате добавления указанного интервала времени к значению даты и времени, представленному текущим объектом. |
| [AddDays](./adddays/)(double) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества дней. |
| [AddHours](./addhours/)(double) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества часов. |
| [AddMilliseconds](./addmilliseconds/)(double) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества миллисекунд. |
| [AddMinutes](./addminutes/)(double) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества минут. |
| [AddMonths](./addmonths/)(int) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества месяцев. |
| [AddSeconds](./addseconds/)(double) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества секунд. |
| [AddTicks](./addticks/)(int64_t) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного количества интервалов в 100 наносекунд. |
| [AddYears](./addyears/)(int) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, равное значению, представленному текущим объектом, с увеличенным на указанное число компонентом года. |
| static [Compare](./compare/)(DateTime, DateTime) | Сравнивает два значения, представленные указанными экземплярами класса [DateTime](./), и возвращает значение, указывающее относительные позиции значений на временной шкале. |
| [CompareTo](./compareto/)(DateTime) const | Сравнивает два значения даты и времени, представленные текущим объектом и указанным экземпляром класса [DateTime](./), и возвращает значение, указывающее относительные положения значений на временной шкале. |
| [DateTime](./datetime/)() | Создаёт экземпляр, представляющий наименьшее возможное значение даты и времени, равное MinValue. |
| [DateTime](./datetime/)(int, int, int) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем и днём. |
| [DateTime](./datetime/)(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем и днём в указанном календаре. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой. |
| [DateTime](./datetime/)(int, int, int, int, int, int, DateTimeKind) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой в указанном календаре. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, DateTimeKind) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой, секундой и миллисекундой. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой, секундой и миллисекундой в указанном календаре. |
| [DateTime](./datetime/)(int64_t, DateTimeKind) | Создаёт экземпляр, представляющий значение даты и времени, заданное числом тиков. |
| [DateTime](./datetime/)(int64_t, DateTimeKind, bool) | Создаёт экземпляр, представляющий значение даты и времени, заданное числом тиков. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [DateTime](./datetime/)(const DateTime\&) | Создаёт копию экземпляра. |
| static [DaysInMonth](./daysinmonth/)(int, int) | Возвращает количество дней в указанном месяце указанного года. |
| static [Equals](./equals/)(DateTime, DateTime) | Определяет, представляют ли указанные экземпляры класса [DateTime](./) одинаковое значение даты и времени. |
| [Equals](./equals/)(DateTime) const | Определяет, представляет ли указанный экземпляр класса [DateTime](./) то же значение даты и времени, что и текущий объект. |
| static [FromBinary](./frombinary/)(int64_t) | Десериализует значение даты и времени из указанного беззнакового 64‑битного целого числа и устанавливает новое значение экземпляра класса [DateTime](./) равным этому значению. |
| static [FromFileTime](./fromfiletime/)(int64_t) | Преобразует указанное файловое время в экземпляр класса [DateTime](./), представляющий то же значение даты и времени, что и локальное время. |
| static [FromFileTimeUtc](./fromfiletimeutc/)(int64_t) | Преобразует указанное файловое время в экземпляр класса [DateTime](./), представляющий то же значение даты и времени, что и время UTC. |
| static [FromOADate](./fromoadate/)(double) | Возвращает экземпляр класса [DateTime](./), представляющий значение даты и времени, эквивалентное указанной дате OLE Automation. |
| static [FromUnixTime](./fromunixtime/)(time_t) | Преобразует указанное значение времени Unix в экземпляр класса [DateTime](./). ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [get_Date](./get_date/)() const | Возвращает новый экземпляр класса [DateTime](./), представляющий дату из значения даты и времени текущего объекта, при этом все компоненты времени устанавливаются в 0. |
| [get_Day](./get_day/)() const | Возвращает порядковый номер дня в месяце, представленный текущим объектом. |
| [get_DayOfWeek](./get_dayofweek/)() const | Возвращает значение, представляющее день недели, представленный текущим объектом. |
| [get_DayOfYear](./get_dayofyear/)() const | Возвращает порядковый номер дня в году, представленный текущим объектом. |
| [get_Hour](./get_hour/)() const | Возвращает компонент часа значения даты и времени, представленного текущим объектом. |
| [get_Kind](./get_kind/)() const | Возвращает значение, указывающее, является ли дата и время, представленные текущим объектом, локальными, временем UTC или ни тем, ни другим. |
| [get_Millisecond](./get_millisecond/)() const | Возвращает компонент миллисекунд значения даты и времени, представленного текущим объектом. |
| [get_Minute](./get_minute/)() const | Возвращает компонент минут значения даты и времени, представленного текущим объектом. |
| [get_Month](./get_month/)() const | Возвращает порядковый номер месяца в году, представленного текущим объектом. |
| static [get_Now](./get_now/)() | Возвращает экземпляр класса [DateTime](./), представляющий текущее время как локальное. |
| [get_Second](./get_second/)() const | Возвращает компонент секунд значения даты и времени, представленного текущим объектом. |
| [get_Ticks](./get_ticks/)() const | Возвращает количество интервалов по 100 наносекунд, прошедших с 0:00:00 UTC, 1 января 0001 года по григорианскому календарю до даты и времени, представленных текущим объектом. |
| [get_TimeOfDay](./get_timeofday/)() const | Возвращает значение, представляющее интервал времени от начала дня, представленного текущим объектом, до даты и времени, представленных текущим объектом. |
| static [get_Today](./get_today/)() | Возвращает экземпляр класса [DateTime](./), представляющий текущую дату, при этом каждый компонент временной части значения, представленного объектом, установлен в 0. |
| static [get_UtcNow](./get_utcnow/)() | Возвращает экземпляр класса [DateTime](./), представляющий текущее время в формате UTC. |
| [get_Year](./get_year/)() const | Возвращает год, представленный текущим объектом. |
| [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Получает части даты. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [GetDateTimeFormats](./getdatetimeformats/)() const | Возвращает массив строк, где каждый элемент — строковое представление текущего объекта, отформатированное с помощью одного из стандартных спецификаторов формата даты и времени. |
| [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Возвращает массив строк, где каждый элемент — строковое представление текущего объекта, отформатированное с указанным стандартным спецификатором формата даты и времени. |
| [GetDateTimeFormats](./getdatetimeformats/)(const SharedPtr\<IFormatProvider\>\&) const | Возвращает массив строк, где каждый элемент — строковое представление текущего объекта, отформатированное с помощью одного из стандартных спецификаторов формата даты и времени и указанного поставщика формата. |
| [GetDateTimeFormats](./getdatetimeformats/)(char_t, const SharedPtr\<IFormatProvider\>\&) const | Возвращает массив строк, где каждый элемент — строковое представление текущего объекта, отформатированное с указанным стандартным спецификатором формата даты и времени и поставщиком формата. |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код для текущего объекта. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Определяет, попадает ли значение даты и времени, представленного текущим объектом, в диапазон перехода на летнее время для текущего часового пояса. |
| static [IsLeapYear](./isleapyear/)(int) | Определяет, является ли указанный год високосным. |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(DateTime) const | Определяет, представляют ли текущий объект и указанный объект [DateTime](./) разные значения даты и времени. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного интервала времени. |
| [operator+=](./operator+=/)(TimeSpan) | Устанавливает текущий объект в значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного интервала времени. |
| [operator-](./operator-/)(TimeSpan) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате вычитания указанного интервала времени из значения, представленного текущим объектом. |
| [operator-](./operator-/)(DateTime) const | Возвращает экземпляр класса [TimeSpan](../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами. |
| [operator-=](./operator-=/)(TimeSpan) | Устанавливает текущий объект в значение даты и времени, полученное в результате вычитания указанного интервала времени из значения даты и времени, представленного текущим объектом. |
| [operator<](./operator_/)(DateTime) const | Определяет, представляет ли текущий объект значение даты и времени, которое предшествует значению, представленному указанным объектом [DateTime](./). |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(DateTime) const | Определяет, представляет ли текущий объект значение даты и времени, которое предшествует или равно значению, представленному указанным объектом [DateTime](./). |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const DateTime\&) | Присваивает значение, представленное указанным экземпляром [DateTime](./), текущему объекту. |
| [operator==](./operator==/)(DateTime) const | Определяет, представляют ли текущий объект и указанный объект [DateTime](./) одинаковое значение даты и времени. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(DateTime) const | Определяет, представляет ли текущий объект значение даты и времени, которое позже значения, представленного указанным объектом [DateTime](./). |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(DateTime) const | Определяет, представляет ли текущий объект значение даты и времени, которое позже или равно значению, представленного указанным объектом [DateTime](./). |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./). |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя информацию о формате, специфичную для культуры. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя указанный формат и информацию о формате, специфичную для культуры. Формат строкового представления должен точно соответствовать указанному формату. Выбрасывает исключение, если преобразование не удалось. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя указанные форматы, информацию о формате, специфичную для культуры, и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов. Выбрасывает исключение, если преобразование не удалось. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [SpecifyKind](./specifykind/)(DateTime, DateTimeKind) | Создаёт новый объект [DateTime](./), который представляет то же количество тиков, что и указанный объект [DateTime](./), и представляет локальное время, время UTC или ни то ни другое, как указано аргументом **kind**. |
| [Subtract](./subtract/)(TimeSpan) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате вычитания указанного интервала времени из значения, представленного текущим объектом. |
| [Subtract](./subtract/)(DateTime) const | Возвращает экземпляр класса [TimeSpan](../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами. |
| [ToBinary](./tobinary/)() const | Сериализует текущий объект. |
| [ToFileTime](./tofiletime/)() const | Возвращает значение, представляющее дату и время, представленные текущим объектом, в виде файлового времени. |
| [ToFileTimeUtc](./tofiletimeutc/)() const | Преобразует значение даты и времени, представленные текущим объектом, в файловое время UTC. |
| [ToLocalTime](./tolocaltime/)() const | Возвращает новый экземпляр класса [DateTime](./), который представляет дату и время, представленные текущим объектом, как локальное время. |
| [ToLongDateString](./tolongdatestring/)() const | Возвращает строку, содержащую полное строковое представление даты текущего объекта. |
| [ToLongTimeString](./tolongtimestring/)() const | Возвращает строку, содержащую полное строковое представление времени текущего объекта. |
| [ToOADate](./tooadate/)() const | Возвращает значение даты и времени, представленных текущим объектом, в виде OLE Automation Date. |
| [ToShortDateString](./toshortdatestring/)() const | Возвращает строку, содержащую краткое строковое представление даты текущего объекта. |
| [ToShortTimeString](./toshorttimestring/)() const | Возвращает строку, содержащую краткое строковое представление времени текущего объекта. |
| [ToString](./tostring/)() const | Возвращает строковое представление значения даты и времени, представленного текущим объектом, с использованием правил форматирования, определённых текущей культурой. |
| [ToString](./tostring/)(const String\&) const | Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя указанный формат и правила форматирования, определённые текущей культурой. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя указанную информацию о формате. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Возвращает строковое представление значения даты и времени, представленного текущим объектом, используя указанную информацию о формате. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToUniversalTime](./touniversaltime/)() const | Возвращает новый экземпляр класса [DateTime](./), который представляет дату и время, представленные текущим объектом, как UTC. |
| [ToUnixTime](./tounixtime/)() const | Возвращает значение, представляющее дату и время, представленные текущим объектом, в виде Unix‑времени. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| static [TryParse](./tryparse/)(const String\&, DateTime\&) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./). |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя указанную информацию о формате, специфичную для культуры, и стиль. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя указанный формат, информацию о формате, специфичную для культуры, и стиль. Формат строкового представления должен точно соответствовать указанному формату. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Преобразует указанное строковое представление даты и времени в эквивалентный объект [DateTime](./), используя указанные форматы, сведения о культуре и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [Type](./type/)() | Возвращает объект [TypeInfo](../typeinfo/), содержащий информацию об этом классе. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Количество 100-наносекунд в интервале времени между минимально возможным и максимально возможным значением [DateTime](./). |
| static [MaxValue](./maxvalue/) | Экземпляр класса [DateTime](./), представляющий максимально возможную дату и время. |
| static constexpr [MinTicks](./minticks/) | Минимальное количество тиков, которое может представлять экземпляр класса [DateTime](./). |
| static [MinValue](./minvalue/) | Экземпляр класса [DateTime](./), представляющий минимально возможную дату и время. |
| static constexpr [TicksPerDay](./ticksperday/) | Количество тиков в дне. |
| static constexpr [TicksPerHour](./ticksperhour/) | Количество тиков в часе. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Количество тиков в микросекунде. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Количество тиков в миллисекунде. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Количество тиков в минуте. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Количество тиков в секунде. |
| static [UnixEpoch](./unixepoch/) | Экземпляр класса [DateTime](./), представляющий начало эпохи Unix (1970.01.01 00:00:00). |
## Примечания



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Создайте экземпляр класса 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Выведите экземпляр в нескольких форматах.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
This code example produces the following output:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
