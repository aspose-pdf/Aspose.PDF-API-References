---
title: "System::ConsoleOutput-klass"
linktitle: "ConsoleOutput"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ConsoleOutput-klass. Representerar standardutmatningsströmmen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1600
url: /sv/cpp/system/consoleoutput/
---
## ConsoleOutput class


Representerar standardutmatningsströmmen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Returnerar alltid ASCII-kodning. |
| [Write](./write/)(bool) override | Skriver ut strängrepresentationen av det angivna bool-värdet till utmatningsströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Skriver ut strängrepresentationen av det angivna objektet till utmatningsströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(char_t) override | Skriver ut det angivna teckenvärdet till utmatningsströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(Decimal) override | Skriver ut strängrepresentationen av [Decimal](../decimal/)-värdet till utmatningsströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(double) override | Skriver ut strängrepresentationen av ett dubbelprecisions-flytande-punktvärde till utmatningsströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(int32_t) override | Skriver ut strängrepresentationen av 32-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(int64_t) override | Skriver ut strängrepresentationen av 64-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(float) override | Skriver ut strängrepresentationen av enkelprecision flyttalvärde till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const String\&) override | Skriver ut det angivna strängobjektet till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(uint32_t) override | Skriver ut strängrepresentationen av osignerat 32-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(uint64_t) override | Skriver ut strängrepresentationen av osignerat 64-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Skriver ut strängrepresentationen av den angivna teckenarrayen till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Skriver ut strängrepresentationen av ett intervall av värden i den angivna teckenarrayen till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const char_t *) override | Skriver ut den angivna c-strängen till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const TypeInfo\&) override | Skriver ut strängrepresentationen av det angivna [TypeInfo](../typeinfo/)‑objektet till utdataströmmen som representeras av det aktuella objektet. |
| [Write](./write/)(const char *) |  |
| [WriteLine](./writeline/)() override | Skriver ut den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Skriver ut strängrepresentationen av det angivna objektet följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(bool) override | Skriver ut strängrepresentationen av det angivna bool‑värdet följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(char_t) override | Skriver ut det angivna teckenvärdet följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(Decimal) override | Skriver ut strängrepresentationen av [Decimal](../decimal/)‑värdet följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(double) override | Skriver ut strängrepresentationen av dubbelprecision flyttalvärde följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(int) override | Skriver ut strängrepresentationen av 32-bitars heltalsvärde följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(int64_t) override | Skriver ut strängrepresentationen av 64-bitars heltalsvärde följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(float) override | Skriver ut strängrepresentationen av enkelprecision flyttalvärde följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const String\&) override | Skriver ut det angivna strängobjektet följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(uint32_t) override | Skriver ut strängrepresentationen av osignerat 32-bitars heltalsvärde följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(uint64_t) override | Skriver ut strängrepresentationen av osignerat 64-bitars heltalsvärde följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Skriver ut strängrepresentationen av den angivna teckenarrayen följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Skriver ut strängrepresentationen av ett intervall av värden i den angivna teckenarrayen följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const char_t *) override | Skriver ut den angivna c-strängen följt av den aktuella radavslutaren till utdataströmmen som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const TypeInfo\&) override | Skriver ut strängrepresentationen av det angivna [TypeInfo](../typeinfo/)‑objektet följt av den aktuella radavslutaren till den utmatningsström som representeras av det aktuella objektet. |
| [WriteLine](./writeline/)(const char *) |  |
## Se även

* Class [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
