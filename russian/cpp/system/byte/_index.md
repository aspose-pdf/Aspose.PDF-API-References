---
title: "Класс System::Byte"
linktitle: "Byte"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Byte. Содержит методы для работы с беззнаковым 8-битным целым числом в C++."
type: docs
weight: 1200
url: /ru/cpp/system/byte/
---
## Byte class


Содержит методы для работы с беззнаковым 8-битным целым числом.

```cpp
class Byte
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Parse](./parse/)(const String\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое, используя предоставленную информацию о форматировании. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое, используя предоставленную информацию о форматировании и стиль числа. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, std::nullptr_t) |  |
| static [TryParse](./tryparse/)(const String\&, uint8_t\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое, используя предоставленную информацию о форматировании и стиль числа. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) |  |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Наибольшее возможное значение. |
| static constexpr [MinValue](./minvalue/) | Наименьшее возможное значение. |
## Примечания



```cpp
#include <system/byte.h>

using namespace System;

int main()
{
  auto b1 = Byte::Parse(u"123");
  std::cout << static_cast<uint32_t>(b1) << std::endl;

  try
  {
    auto b2 = Byte::Parse(u"345");
    std::cout << static_cast<uint32_t>(b2) << std::endl;
  }
  catch (const OverflowException &ex)
  {
    std::cerr << ex.what() << std::endl;
  }

  uint8_t b3 = 0;
  if (Byte::TryParse(u"10", b3))
  {
    std::cout << static_cast<uint32_t>(b3) << std::endl;
  }
  else
  {
    std::cerr << "Something went wrong." << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
123
System::OverflowException: Value was either too large or too small for an UInt8
10
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
