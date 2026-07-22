---
title: "System::Text::ICUDecoder-klass"
linktitle: "ICUDecoder"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUDecoder-klass. Avkodare som använder ICU för avkodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2000
url: /sv/cpp/system.text/icudecoder/
---
## ICUDecoder class


[Decoder](../decoder/) that uses ICU for decoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUDecoder : public System::Text::Decoder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Konverterar byte till tecken. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Konverterar byte till tecken. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Hämtar antalet tecken som behövs för att avkoda en buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Hämtar antalet tecken som behövs för att avkoda en buffer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Hämtar antalet tecken som behövs för att avkoda en buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Hämta tecknen som resultat av att avkoda en buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Hämta tecknen som resultat av att avkoda en buffer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Hämta tecknen som resultat av att avkoda en buffer. |
| [ICUDecoder](./icudecoder/)(ICUEncoding *) | Konstruktor. |
| virtual [Reset](./reset/)() | Ställer in interna variabler till ursprungligt tillstånd. |
| virtual [~ICUDecoder](./~icudecoder/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Base](./base/) | [Base](./base/) typ. |
## Se även

* Class [Decoder](../decoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
