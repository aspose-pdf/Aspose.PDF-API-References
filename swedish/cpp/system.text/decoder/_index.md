---
title: "System::Text::Decoder klass"
linktitle: "Decoder"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::Decoder klass. Inkapslar avkodning av byte‑sekvens till tecken‑sekvens. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.text/decoder/
---
## Decoder class


Inkapslar avkodning av byte‑sekvens till tecken‑sekvens. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Decoder : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Konverterar byte till tecken. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Konverterar byte till tecken. |
| [get_Fallback](./get_fallback/)() const | Hämtar felhanteringsfallback. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Hämtar fallback‑buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Hämtar antalet tecken som behövs för att avkoda en buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Hämtar antalet tecken som behövs för att avkoda en buffer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Hämtar antalet tecken som behövs för att avkoda en buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Hämta tecknen som resultat av att avkoda en buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Hämta tecknen som resultat av att avkoda en buffer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Hämta tecknen som resultat av att avkoda en buffer. |
| virtual [Reset](./reset/)() | Rensar kodarens interna tillstånd. |
| [set_Fallback](./set_fallback/)(const DecoderFallbackPtr\&) | Ställer in felhanteringsfallback. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
