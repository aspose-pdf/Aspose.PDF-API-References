---
title: "System::Text::ICUEncoding class"
linktitle: "ICUEncoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUEncoding-klass. ICU-baserad kodningsimplementation. FÖR INTERNT ANVÄNDANDE. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2200
url: /sv/cpp/system.text/icuencoding/
---
## ICUEncoding class


ICU-baserad kodningsimplementation. FÖR INTERNT ANVÄNDANDE. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetByteCount](./getbytecount/)(const char_t *, int) override | Hämta antalet tecken som behövs för att koda en teckenbuffert. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | RTTI. |
| [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) override | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const String\&) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| [GetCharCount](./getcharcount/)(const uint8_t *, int) override | Hämta antalet tecken som behövs för att avkoda en bytebuffert. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Hämta antalet tecken som behövs för att avkoda en bytebuffert. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Hämta antalet tecken som behövs för att avkoda en bytebuffert. |
| [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) override | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| [GetDecoder](./getdecoder/)() override | Hämta en avkodare som vidarebefordrar förfrågningar till detta objekt. |
| [GetEncoder](./getencoder/)() override | Hämta en kodare som vidarebefordrar förfrågningar till detta objekt. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Hämta det maximala antalet byte som behövs för att koda ett angivet antal tecken. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Hämta det maximala antalet tecken som behövs för att avkoda ett angivet antal byte. |
| [GetPreamble](./getpreamble/)() override | Returnerar en sekvens av byte som anger kodningen (t.ex. BOM). |
| [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| [operator==](./operator==/)(const ICUEncoding\&) const | Jämför kodningar med hjälp av kodsidor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardvärde för kodsida. |
## Se även

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
