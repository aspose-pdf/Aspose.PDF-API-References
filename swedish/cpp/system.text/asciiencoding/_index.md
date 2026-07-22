---
title: "System::Text::ASCIIEncoding klass"
linktitle: "ASCIIEncoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ASCIIEncoding-klass. Representerar ASCII‑kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.text/asciiencoding/
---
## ASCIIEncoding class


Representerar ASCII‑kodning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/)() | Konstruktor. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Hämtar maximalt antal byte som behövs för att lagra en sträng med känt teckenantal. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Hämta det maximala antalet tecken som behövs för att avkoda ett angivet antal byte. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardvärde för kodsida. |
## Se även

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
