---
title: "System::Byte class"
linktitle: "Byte"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Byte class. Contiene métodos para trabajar con el entero sin signo de 8 bits en C++."
type: docs
weight: 1200
url: /es/cpp/system/byte/
---
## Byte class


Contiene métodos para trabajar con el entero sin signo de 8 bits.

```cpp
class Byte
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Parse](./parse/)(const String\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente usando la información de formato proporcionada. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente usando la información de formato proporcionada y el estilo numérico. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, std::nullptr_t) |  |
| static [TryParse](./tryparse/)(const String\&, uint8_t\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al entero sin signo de 8 bits equivalente usando la información de formato proporcionada y el estilo numérico. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valor máximo posible. |
| static constexpr [MinValue](./minvalue/) | Valor mínimo posible. |
## Observaciones



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

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
