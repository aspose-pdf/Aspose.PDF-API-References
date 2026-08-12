---
title: "System::Byte-klass"
linktitle: "Byte"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Byte-klass. Innehåller metoder för att arbeta med den osignerade 8‑bit‑heltalet i C++."
type: docs
weight: 1200
url: /sv/cpp/system/byte/
---
## Byte class


Innehåller metoder för att arbeta med den osignerade 8‑bitars heltalet.

```cpp
class Byte
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Parse](./parse/)(const String\&) | Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal med hjälp av den angivna formateringsinformationen. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal med hjälp av den angivna formateringsinformationen och talstilen. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, std::nullptr_t) |  |
| static [TryParse](./tryparse/)(const String\&, uint8_t\&) | Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) | Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal med hjälp av den angivna formateringsinformationen och talstilen. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Största möjliga värde. |
| static constexpr [MinValue](./minvalue/) | Minsta möjliga värde. |
## Anmärkningar



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

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
