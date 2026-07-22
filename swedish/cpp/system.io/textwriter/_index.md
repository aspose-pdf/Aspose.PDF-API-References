---
title: "System::IO::TextWriter‑klass"
linktitle: "TextWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::TextWriter‑klass. En basklass för klasser som representerar skribenter som skriver sekvenser av tecken till olika destinationer. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2700
url: /sv/cpp/system.io/textwriter/
---
## TextWriter class


En basklass för klasser som representerar skribenter som skriver sekvenser av tecken till olika destinationer. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TextWriter : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Close](./close/)() | Stänger strömmen och frigör förvärvade resurser. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual [Flush](./flush/)() | Spolar innehållet i bufferten till den underliggande strömmen. |
| virtual [get_Encoding](./get_encoding/)() | Returnerar den för närvarande använda kodningen. |
| virtual [get_FormatProvider](./get_formatprovider/)() const | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| [get_FormatProvider](./get_formatprovider/)() | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| virtual [get_NewLine](./get_newline/)() const | Returnerar en radavslutningssträng. |
| [get_NewLine](./get_newline/)() | Returnerar en radavslutningssträng. |
| virtual [set_NewLine](./set_newline/)(const System::String\&) | Ställer in en radavslutningssträng. |
| virtual [Write](./write/)(const SharedPtr\<Object\>\&) | Skriver strängrepresentationen av det angivna objektet till strömmen. |
| virtual [Write](./write/)(bool) | Skriver strängrepresentationen av det angivna booleska värdet till strömmen. |
| virtual [Write](./write/)(char_t) | Skriver det angivna tecknet till strömmen. |
| virtual [Write](./write/)(Decimal) | Skriver strängrepresentationen av det angivna [Decimal](../../system/decimal/)-objektet till strömmen. |
| virtual [Write](./write/)(double) | Skriver strängrepresentationen av det angivna dubbelprecision flyttalvärdet till strömmen. |
| virtual [Write](./write/)(int) | Skriver strängrepresentationen av det angivna 32‑bit heltalsvärdet till strömmen. |
| virtual [Write](./write/)(int64_t) | Skriver strängrepresentationen av det angivna 64‑bit heltalsvärdet till strömmen. |
| virtual [Write](./write/)(float) | Skriver strängrepresentationen av det angivna enkelprecision flyttalvärdet till strömmen. |
| virtual [Write](./write/)(const String\&) | Skriver den angivna strängen till strömmen. |
| virtual [Write](./write/)(uint32_t) | Skriver strängrepresentationen av det angivna teckenlösa 32‑bit heltalsvärdet till strömmen. |
| virtual [Write](./write/)(uint64_t) | Skriver strängrepresentationen av det angivna teckenlösa 64‑bit heltalsvärdet till strömmen. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&) | Skriver alla tecken från den angivna arrayen till strömmen. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Skriver det angivna delintervallet av UTF-16‑tecken från den angivna teckenarrayen till strömmen. |
| virtual [Write](./write/)(const char_t *) | Skriver den angivna c‑strängen till strömmen. |
| virtual [Write](./write/)(const TypeInfo\&) | Skriver strängrepresentationen av det angivna [TypeInfo](../../system/typeinfo/)-objektet till strömmen. |
| [Write](./write/)(const String\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet till strömmen. |
| virtual [WriteLine](./writeline/)() | Skriver radavslutningstecken till strömmen. |
| virtual [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) | Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(bool) | Skriver strängrepresentationen av det angivna booleska värdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(char_t) | Skriver det angivna tecknet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(Decimal) | Skriver strängrepresentationen av det angivna [Decimal](../../system/decimal/)-objektet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(double) | Skriver den strängrepresentation av det angivna dubbelprecision flyttalvärdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(int) | Skriver den strängrepresentation av det angivna 32-bitars heltalsvärdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(int64_t) | Skriver den strängrepresentation av det angivna 64-bitars heltalsvärdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(float) | Skriver den strängrepresentation av det angivna enkelprecision flyttalvärdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(const String\&) | Skriver den angivna strängen följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(uint32_t) | Skriver den strängrepresentation av det angivna teckenlösa 32-bitars heltalsvärdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(uint64_t) | Skriver den strängrepresentation av det angivna teckenlösa 64-bitars heltalsvärdet följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Skriver alla tecken från den angivna arrayen följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(const char_t *) | Skriver den angivna c-strängen följt av radavslutningstecknen till strömmen. |
| virtual [WriteLine](./writeline/)(const TypeInfo\&) | Skriver den strängrepresentation av det angivna [TypeInfo](../../system/typeinfo/)-objektet följt av radavslutningstecknen till strömmen. |
| [WriteLine](./writeline/)(const String\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet följt av radavslutningstecknen till strömmen. |
| virtual [~TextWriter](./~textwriter/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till denna klass. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
