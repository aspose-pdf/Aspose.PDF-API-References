---
title: "Класс System::Decimal"
linktitle: "Decimal"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Decimal. Представляет десятичное число. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 2000
url: /ru/cpp/system/decimal/
---
## Decimal class


Представляет десятичное число. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class Decimal
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Add](./add/)(const Decimal\&, const Decimal\&) | Складывает два указанных значения [Decimal](./). |
| static [Ceiling](./ceiling/)(const Decimal\&) | Возвращает наименьшее целое значение, которое больше или равно указанному значению. |
| static [Compare](./compare/)(const Decimal\&, const Decimal\&) | Определяет, меньше ли, равно ли или больше значение, представленное первым объектом [Decimal](./), чем значение, представленное вторым объектом [Decimal](./). |
| [CompareTo](./compareto/)(const Decimal\&) const | Определяет, меньше ли, равно ли или больше значение, представленное текущим объектом, чем значение, представленное указанным объектом. |
| [Decimal](./decimal/)() | Создает экземпляр, представляющий 0. |
| [Decimal](./decimal/)(std::int8_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::int16_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::int32_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::int64_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint8_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint16_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint32_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint64_t) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(float) | Создает экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(double) | Создает экземпляр, представляющий указанное значение. |
| explicit [Decimal](./decimal/)(const std::string\&) | Создает экземпляр, представляющий значение, строковое представление которого указано как экземпляр класса std::string. |
| [Decimal](./decimal/)(int32_t, int32_t, int32_t, bool, uint8_t) | Создает объект [Decimal](./) из указанных компонентов. |
| [Decimal](./decimal/)(const Decimal\&) | Создает экземпляр класса [Decimal](./), представляющий то же число, что и указанный объект [Decimal](./). |
| [Decimal](./decimal/)(const ArrayPtr\<int32_t\>\&) | Создает экземпляр класса [Decimal](./) из массива целых чисел, содержащего двоичное представление. |
| [Decimal](./decimal/)(std::nullptr_t) | Всегда генерирует ArgumentNullException. |
| [Decimal](./decimal/)(const number_type\&) | Создает экземпляр класса [Decimal](./), представляющий указанное значение. |
| static [Divide](./divide/)(const Decimal\&, const Decimal\&) | Делит два указанных значения [Decimal](./). |
| [Equals](./equals/)(const Decimal\&) const | Определяет, равны ли значения, представленные текущим объектом и указанным объектом. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Определяет, равны ли значения, представленные текущим объектом и указанным объектом. |
| static [Equals](./equals/)(const Decimal\&, const Decimal\&) | Определяет, равны ли значения, представленные указанными объектами. |
| static [Floor](./floor/)(const Decimal\&) | Возвращает наибольшее целое значение, которое меньше или равно указанному значению. |
| static [FromOACurrency](./fromoacurrency/)(int64_t) | [Convert](../convert/) указанное значение валюты OLE в эквивалентное значение [Decimal](./). НЕ РЕАЛИЗОВАНО. |
| static [GetBits](./getbits/)(const Decimal\&) | Преобразует указанный объект [Decimal](./) в двоичное представление его значения. |
| static [GetBytes](./getbytes/)(const Decimal\&, const System::ArrayPtr\<uint8_t\>\&) | [Convert](../convert/) указанное значение [Decimal](./) в массив байтов. |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код для текущего объекта. |
| [GetTypeCode](./gettypecode/)() const | Получает код типа объекта. |
| static [Multiply](./multiply/)(const Decimal\&, const Decimal\&) | Умножает два указанных значения [Decimal](./). |
| static [Negate](./negate/)(const Decimal\&) | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате отрицания значения, представленного указанным объектом. |
| explicit [operator bool](./operatorbool/)() const | Преобразует значение, представленное текущим объектом, в логическое значение. |
| explicit [operator double](./operatordouble/)() const | Преобразует значение, представленное текущим объектом, в число двойной точности с плавающей запятой. |
| explicit [operator float](./operatorfloat/)() const | Преобразует значение, представленное текущим объектом, в число одинарной точности с плавающей запятой. |
| [operator!=](./operator!=/)(const Decimal\&) const | Определяет, не равны ли значения, представленные текущим объектом и указанным объектом. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Определяет, отличается ли значение, представленное текущим объектом, от 0. |
| [operator%](./operator%/)(const Decimal\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате операции взятия остатка от деления значений, представленных текущим и указанным объектами. |
| [operator%=](./operator%=/)(const Decimal\&) | Присваивает текущему объекту новое значение, полученное в результате операции взятия остатка от деления значений, представленных текущим и указанным объектами. |
| [operator*](./operator_/)(const Decimal\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате умножения значений, представленных текущим и указанным объектами. |
| [operator*=](./operator_=/)(const Decimal\&) | Назначает текущему объекту новое значение, которое является результатом умножения значений, представленных текущим и указанным объектами. |
| [operator+](./operator+/)(const Decimal\&) const | Возвращает новый экземпляр класса [Decimal](./), который представляет значение, являющееся суммой значений, представленных текущим и указанным объектами. |
| [operator++](./operator++/)() | Увеличивает значение, представляемое текущим объектом. |
| [operator+=](./operator+=/)(const Decimal\&) | Назначает текущему объекту новое значение, которое является суммой значений, представленных текущим и указанным объектами. |
| [operator-](./operator-/)(const Decimal\&) const | Возвращает новый экземпляр класса [Decimal](./), который представляет значение, являющееся результатом вычитания значения, представленного указанным объектом, из значения, представленного текущим объектом. |
| [operator-](./operator-/)() const | Возвращает новый экземпляр класса [Decimal](./), который представляет значение, полученное в результате отрицания значения, представленного текущим объектом. |
| [operator--](./operator--/)() | Уменьшает значение, представляемое текущим объектом. |
| [operator-=](./operator-=/)(const Decimal\&) | Назначает текущему объекту новое значение, которое является результатом вычитания значения, представленного указанным объектом, из значения, представленного текущим объектом. |
| [operator/](./operator//)(const Decimal\&) const | Возвращает новый экземпляр класса [Decimal](./), который представляет значение, являющееся результатом деления значения, представленного текущим объектом, на значение, представленного указанным объектом. |
| [operator/=](./operator/=/)(const Decimal\&) | Назначает текущему объекту новое значение, которое является результатом деления значения, представленного текущим объектом, на значение, представленного указанным объектом. |
| [operator<](./operator_/)(const Decimal\&) const | Определяет, меньше ли значение, представляемое текущим объектом, чем значение, представляемое указанным объектом. |
| [operator<=](./operator_=/)(const Decimal\&) const | Определяет, меньше ли или равно значение, представляемое текущим объектом, значению, представленному указанным объектом. |
| [operator=](./operator=/)(const Decimal\&) | Назначает значение, представленное указанным объектом, текущему объекту. |
| [operator==](./operator==/)(const Decimal\&) const | Определяет, равны ли значения, представленные текущим объектом и указанным объектом. |
| [operator==](./operator==/)(std::nullptr_t) const | Определяет, равно ли значение, представляемое текущим объектом, нулю. |
| [operator>](./operator_/)(const Decimal\&) const | Определяет, больше ли значение, представляемое текущим объектом, чем значение, представляемое указанным объектом. |
| [operator>=](./operator_=/)(const Decimal\&) const | Определяет, больше ли или равно значение, представляемое текущим объектом, значению, представленному указанным объектом. |
| static [Parse](./parse/)(const String\&) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./). |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./), используя указанный стиль. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./), используя указанный поставщик формата. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./), используя указанный стиль и поставщик формата. |
| static [Remainder](./remainder/)(const Decimal\&, const Decimal\&) | Вычисляет остаток от деления двух значений [Decimal](./). |
| static [Round](./round/)(const Decimal\&, MidpointRounding) | Округляет указанное значение до ближайшего целого числа. Параметр определяет поведение функции, если указанное значение одинаково близко к двум ближайшим числам. |
| static [Round](./round/)(const Decimal\&, int, MidpointRounding) | Округляет указанное значение до ближайшего значения с указанным числом знаков после запятой. Параметр определяет поведение функции, если указанное значение одинаково близко к двум ближайшим числам. |
| static [Subtract](./subtract/)(const Decimal\&, const Decimal\&) | Вычитает одно указанное значение [Decimal](./) из другого. |
| static [ToByte](./tobyte/)(Decimal) | Преобразует значение [Decimal](./) в беззнаковое 8-битное целое значение. |
| static [ToDouble](./todouble/)(Decimal) | Преобразует значение [Decimal](./) в число с плавающей запятой двойной точности. |
| static [ToInt16](./toint16/)(Decimal) | Преобразует значение [Decimal](./) в знаковое 16‑битное целое значение. |
| static [ToInt32](./toint32/)(Decimal) | Преобразует значение [Decimal](./) в знаковое 32‑битное целое значение. |
| static [ToInt64](./toint64/)(Decimal) | Преобразует значение [Decimal](./) в знаковое 64‑битное целое значение. |
| static [ToOACurrency](./tooacurrency/)(const Decimal\&) | [Convert](../convert/) указанное значение [Decimal](./) в эквивалентное значение валюты OLE. НЕ РЕАЛИЗОВАНО. |
| static [ToSByte](./tosbyte/)(Decimal) | Преобразует значение [Decimal](./) в знаковое 8‑битное целое значение. |
| static [ToSingle](./tosingle/)(Decimal) | Преобразует значение [Decimal](./) в число с плавающей запятой одинарной точности. |
| [ToStdString](./tostdstring/)() const | Возвращает экземпляр std::string, содержащий строковое представление значения, представленного объектом. |
| [ToString](./tostring/)() const | Возвращает строковое представление значения, представленного объектом. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Преобразует текущий объект в строку, используя информацию о формате, специфичную для культуры. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const Decimal\&, std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Преобразует текущий объект в его строковое представление, используя указанный строковый формат и информацию о формате, специфичную для культуры, предоставленную указанным объектом [IFormatProvider](../iformatprovider/). |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToStringInternal](./tostringinternal/)() const | Возвращает строковое представление значения, представленного объектом. Для внутреннего использования. |
| static [ToUInt16](./touint16/)(Decimal) | Преобразует значение [Decimal](./) в беззнаковое 16‑битное целое значение. |
| static [ToUInt32](./touint32/)(Decimal) | Преобразует значение [Decimal](./) в беззнаковое 32‑битное целое значение. |
| static [ToUInt64](./touint64/)(Decimal) | Преобразует значение [Decimal](./) в беззнаковое 64‑битное целое значение. |
| static [Truncate](./truncate/)(const Decimal\&) | Возвращает объект [Decimal](./), представляющий значение, у которого целая часть равна целой части значения, представленного указанным объектом [Decimal](./), при этом все дробные цифры отбрасываются. |
| static [TryParse](./tryparse/)(const String\&, Decimal\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](./). |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](./), используя предоставленную информацию о форматировании и стиль числа. |
| static [Type](./type/)() | Возвращает ссылку на объект [TypeInfo](../typeinfo/), представляющий информацию о типе класса [Decimal](./). |
| [~Decimal](./~decimal/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static [MaxValue](./maxvalue/) | Представляет наибольшее число, которое может быть представлено классом [Decimal](./). |
| static [MinusOne](./minusone/) | Представляет число -1. |
| static [MinValue](./minvalue/) | Представляет наименьшее число, которое может быть представлено классом [Decimal](./). |
| static [One](./one/) | Представляет число 1. |
| static [Zero](./zero/) | Представляет число 0. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [number_type](./number_type/) | Псевдоним для Detail::decimal_number_type. |
## Примечания



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
This code example produces the following output:
-79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
