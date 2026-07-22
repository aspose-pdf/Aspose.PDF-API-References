---
title: "System::IO::StringWriter klass"
linktitle: "StringWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StringWriter klass. Implementerar en TextWriter som skriver information till en sträng. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2500
url: /sv/cpp/system.io/stringwriter/
---
## StringWriter class


Implementerar en [TextWriter](../textwriter/) som skriver information till en sträng. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Returnerar den för närvarande använda kodningen. |
| virtual [GetStringBuilder](./getstringbuilder/)() | Returnerar den för närvarande använda StringBuilder. |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) | Skapar en ny instans av [StringWriter](./) med den angivna StringBuilder och [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&) | Skapar en ny instans av [StringWriter](./) med den angivna StringBuilder och [IFormatProvider](../../system/iformatprovider/) från den aktuella kulturen. |
| [StringWriter](./stringwriter/)(const IFormatProviderPtr\&) | Skapar en ny instans av [StringWriter](./) med den angivna [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)() | Skapar en ny instans av [StringWriter](./) med [IFormatProvider](../../system/iformatprovider/) från den aktuella kulturen. |
| [ToString](./tostring/)() const override | Returnerar den underliggande strängen. |
| [Write](./write/)(char_t) override | Skriver det angivna tecknet till strömmen. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av tecken från den angivna teckenarrayen till strömmen. |
| [Write](./write/)(const String\&) override | Skriver den angivna strängen till strömmen. |
## Se även

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
