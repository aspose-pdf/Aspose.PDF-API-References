---
title: "System::Text::ICUEncoder klass"
linktitle: "ICUEncoder"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUEncoder klass. Kodare som använder ICU för kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.text/icuencoder/
---
## ICUEncoder class


[Encoder](../encoder/) that uses ICU for encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUEncoder : public System::Text::Encoder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Konverterar tecken till byte. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Konverterar tecken till byte. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Hämtar antalet byte som behövs för att koda en buffer. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Hämtar antalet byte som behövs för att koda en buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Hämta byte som resultat av att koda en buffer. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Hämta byte som resultat av att koda en buffer. |
| [ICUEncoder](./icuencoder/)(ICUEncoding *) | Konstruktor. |
| virtual [Reset](./reset/)() | Ställer in interna variabler till ursprungligt tillstånd. |
| [~ICUEncoder](./~icuencoder/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Base](./base/) | [Base](./base/) typ. |
## Se även

* Class [Encoder](../encoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
