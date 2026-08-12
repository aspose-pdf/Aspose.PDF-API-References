---
title: "System::Console-klass"
linktitle: "Console"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Console-klass. Tillhandahåller metoder för att skriva ut data till standardutmatningsströmmen. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1500
url: /sv/cpp/system/console/
---
## Console class


Tillhandahåller metoder för att skriva ut data till standardutmatningsströmmen. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Console
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Beep](./beep/)() | INTE IMPLEMENTERAD. |
| static [get_Error](./get_error/)() | Returnerar en delad pekare som pekar på objektet som representerar standard felström. |
| static [get_In](./get_in/)() | Returnerar en delad pekare som pekar på objektet som representerar standard inmatningsström. |
| static [get_Out](./get_out/)() | Returnerar en delad pekare som pekar på objektet som representerar standard utmatningsström. |
| static [Mute](./mute/)(bool) | Stänger av eller slår på standard utmatningsströmmen. |
| static [ReadKey](./readkey/)() | INTE IMPLEMENTERAD. |
| static [set_Title](./set_title/)(const String\&) | Ställer in konsolfönstrets rubrik. |
| static [SetError](./seterror/)(const SharedPtr\<System::IO::TextWriter\>\&) | Tilldelar det angivna objektet till klassens Error‑egenskap. |
| static [SetIn](./setin/)(const SharedPtr\<System::IO::TextReader\>\&) | Ställer in In‑egenskapen till det angivna TextReader‑objektet. |
| static [SetOut](./setout/)(const SharedPtr\<System::IO::TextWriter\>\&) | Tilldelar det angivna objektet till klassens Out‑egenskap. |
| static [Write](./write/)(const SharedPtr\<T\>\&) | Skriver ut strängrepresentationen av det angivna objektet till standard utmatningsströmmen. |
| static [Write](./write/)(bool) | Skriver ut strängrepresentationen av bool value till standardutmatningsströmmen. |
| static [Write](./write/)(char_t) | Skriver ut det angivna teckenvärdet till standardutmatningsströmmen. |
| static [Write](./write/)(const ArrayPtr\<char_t\>\&) | Skriver ut strängrepresentationen av den angivna teckenarrayen till standardutmatningsströmmen. |
| static [Write](./write/)(const Decimal\&) | Skriver ut strängrepresentationen av [Decimal](../decimal/) värde till standardutmatningsströmmen. |
| static [Write](./write/)(double) | Skriver ut strängrepresentationen av double-precision floating-point value till standardutmatningsströmmen. |
| static [Write](./write/)(float) | Skriver ut strängrepresentationen av single-precision floating-point value till standardutmatningsströmmen. |
| static [Write](./write/)(int32_t) | Skriver ut strängrepresentationen av 32‑bitars heltalsvärde till standardutmatningsströmmen. |
| static [Write](./write/)(int64_t) | Skriver ut strängrepresentationen av 64‑bitars heltalsvärde till standardutmatningsströmmen. |
| static [Write](./write/)(const String\&) | Skriver ut det angivna strängobjektet till standardutmatningsströmmen. |
| static [Write](./write/)(const char_t *) | Skriver ut den angivna c‑strängen till standardutmatningsströmmen. |
| static [Write](./write/)(const TypeInfo\&) | Skriver ut strängrepresentationen av [TypeInfo](../typeinfo/) värde till standardutmatningsströmmen. |
| static [Write](./write/)(uint32_t) | Skriver ut strängrepresentationen av osignerat 32‑bitars heltalsvärde till standardutmatningsströmmen. |
| static [Write](./write/)(uint64_t) | Skriver ut strängrepresentationen av osignerat 64‑bitars heltalsvärde till standardutmatningsströmmen. |
| static [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Skriver ut strängrepresentationen av det angivna intervallet av den angivna teckenarrayen till standardutmatningsströmmen. |
| static [Write](./write/)(const String\&, Args\&&...) | Skriver ut strängrepresentationen av de angivna argumenten formaterade enligt det angivna formatet till standardutmatningsströmmen. |
| static [Write](./write/)(const char *) |  |
| static [WriteLine](./writeline/)() | Skriver ut den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const SharedPtr\<T\>\&) | Skriver ut strängrepresentationen av det angivna objektet följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(bool) | Skriver ut strängrepresentationen av bool value följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(char_t) | Skriver ut det angivna teckenvärdet följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Skriver ut strängrepresentationen av den angivna teckenarrayen följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const Decimal\&) | Skriver ut strängrepresentationen av [Decimal](../decimal/) värde följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(double) | Skriver ut strängrepresentationen av double-precision floating-point value följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(float) | Skriver ut strängrepresentationen av single-precision floating-point value följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(int32_t) | Skriver ut strängrepresentationen av 32‑bitars heltalsvärde följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(int64_t) | Skriver ut strängrepresentationen av 64‑bitars heltalsvärde följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const String\&) | Skriver ut det angivna strängobjektet följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const char_t *) | Skriver ut den angivna c-strängen följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const TypeInfo\&) | Skriver ut strängrepresentationen av [TypeInfo](../typeinfo/)‑värdet följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(uint32_t) | Skriver ut strängrepresentationen av ett osignerat 32‑bitars heltal följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(uint64_t) | Skriver ut strängrepresentationen av ett osignerat 64‑bitars heltal följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int, int) | Skriver ut strängrepresentationen av det angivna intervallet av den angivna teckenarrayen följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const Exception\&) | Skriver ut strängrepresentationen av det angivna [Exception](../exception/)-objektet följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const String\&, Args\&&...) | Skriver ut strängrepresentationen av de angivna argumenten formaterade enligt det angivna formatet följt av den aktuella radavslutaren till standardutmatningsströmmen. |
| static [WriteLine](./writeline/)(const char *) |  |
## Anmärkningar



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Skriv ut hej‑meddelandet.
  Console::WriteLine(u"Hello, world!");

  // Skapa en instans av klassen 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Skriv ut elementen i arrayen.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
1 2 3 4 5
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
