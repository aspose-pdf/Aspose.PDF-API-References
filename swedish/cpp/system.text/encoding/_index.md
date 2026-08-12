---
title: "System::Text::Encoding klass"
linktitle: "Encoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::Encoding klass. Kodningstjänster i C++."
type: docs
weight: 1600
url: /sv/cpp/system.text/encoding/
---
## Encoding class


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Clone](./clone/)() | Klonar kodningsobjekt. |
| static [Convert](./convert/)(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) | Konverterar byte mellan två kodningar. |
| static [Convert](./convert/)(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) | Konverterar byte mellan två kodningar. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför kodningar. |
| static [get_ASCII](./get_ascii/)() | Hämtar ASCII‑kodning. |
| static [get_BigEndianUnicode](./get_bigendianunicode/)() | Hämtar det standardiserade big-endian Unicode‑kodningsobjektet. |
| static [get_BigEndianUTF32](./get_bigendianutf32/)() | Hämtar det standardiserade big-endian UTF-32‑kodningsobjektet. |
| virtual [get_BodyName](./get_bodyname/)() | Hämtar kodningsnamn som är kompatibelt med e‑postagentens brödtext. |
| virtual [get_CodePage](./get_codepage/)() | Hämtar [Windows](../../system.windows/) kodsidans ID. |
| [get_DecoderFallback](./get_decoderfallback/)() const | Hämtar avkodarens reserv. |
| static [get_Default](./get_default/)() | Hämtar standardkodning. |
| [get_EncoderFallback](./get_encoderfallback/)() const | Hämtar kodarens reserv. |
| virtual [get_EncodingName](./get_encodingname/)() | Hämtar människoläsbart kodningsnamn. |
| virtual [get_HeaderName](./get_headername/)() | Hämtar kodningsnamn som är kompatibelt med e‑postagentens rubrik. |
| virtual [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Kontrollerar om kodning kan användas i webbläsare för att visa innehåll. |
| virtual [get_IsBrowserSave](./get_isbrowsersave/)() | Kontrollerar om kodning kan användas i webbläsaren för att spara innehåll. |
| virtual [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Kontrollerar om kodning kan användas i e‑postklienten för att visa innehåll. |
| virtual [get_IsMailNewsSave](./get_ismailnewssave/)() | Kontrollerar om kodning kan användas i e‑postklienten för att spara innehåll. |
| [get_IsReadOnly](./get_isreadonly/)() | Kontrollerar om kodning är skrivskyddad. |
| virtual [get_IsSingleByte](./get_issinglebyte/)() | Kontrollerar om kodning är en byte. |
| static [get_Latin1](./get_latin1/)() | Hämtar Latin1‑kodning. FÖR INTERNT ANVÄNDANDE. |
| static [get_Unicode](./get_unicode/)() | Hämtar standardobjektet för Unicode‑kodning. |
| static [get_UTF32](./get_utf32/)() |  |
| static [get_UTF7](./get_utf7/)() | Hämtar standardobjektet för UTF-7‑kodning. |
| static [get_UTF8](./get_utf8/)() | Hämtar standardobjektet för UTF-8‑kodning. |
| static [get_UTF8Unmarked](./get_utf8unmarked/)() | Endast intern, för användning av klassbiblioteken: Omarkerad och utan inmatningsvalidering. |
| virtual [get_WebName](./get_webname/)() | Hämtar IANA‑kompatibelt kodningsnamn. |
| virtual [get_WindowsCodePage](./get_windowscodepage/)() | Hämtar [Windows](../../system.windows/) kodsidans ID. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | Hämta antalet tecken som behövs för att koda en teckenbuffert. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Hämta antalet tecken som behövs för att koda en teckenbuffert. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Hämta antalet tecken som behövs för att koda en teckenbuffert. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | Hämta antalet tecken som behövs för att koda en sträng. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | Hämta antalet tecken som behövs för att koda en teckenbuffert. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int) | Hämta antalet tecken som behövs för att koda en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const String\&) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) | Hämta de byte som erhålls vid kodning av en teckenbuffert. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Hämta antalet tecken som behövs för att avkoda en bytebuffert. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Hämta antalet tecken som behövs för att avkoda en bytebuffert. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int) | Hämta antalet tecken som behövs för att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) | Hämta tecknen som resultat av att avkoda en bytebuffert. |
| virtual [GetDecoder](./getdecoder/)() | Hämta en avkodare som vidarebefordrar förfrågningar till detta objekt. |
| virtual [GetEncoder](./getencoder/)() | Hämta en kodare som vidarebefordrar förfrågningar till detta objekt. |
| static [GetEncoding](./getencoding/)(const String\&) | Hämtar kodning efter namn. |
| static [GetEncoding](./getencoding/)(int) | Hämtar kodning efter kodsida. |
| static [GetEncoding](./getencoding/)(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) | Hämtar kodning efter kodsida. |
| static [GetEncoding](./getencoding/)(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) | Hämtar kodning efter namn. |
| static [GetEncodings](./getencodings/)() | Hämtar lista över kända kodningar. |
| [GetHashCode](./gethashcode/)() const override | Hashar kodning. |
| virtual [GetMaxByteCount](./getmaxbytecount/)(int) | Hämta det maximala antalet byte som behövs för att koda ett angivet antal tecken. |
| virtual [GetMaxCharCount](./getmaxcharcount/)(int) | Hämta det maximala antalet tecken som behövs för att avkoda ett angivet antal byte. |
| virtual [GetPreamble](./getpreamble/)() | Returnerar en sekvens av byte som anger kodningen (t.ex. BOM). |
| virtual [GetString](./getstring/)(uint8_t *, int) | Avkodar en buffert av byte till en sträng. |
| [GetString](./getstring/)(const ReadOnlySpan\<uint8_t\>\&) | Avkodar en buffert av byte till en sträng. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>) | Avkodar en buffert av byte till en sträng. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&) | Avkodar en buffert av byte till en sträng. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>\&) | Avkodar en buffert av byte till en sträng. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>, int, int) | Avkodar en buffert av byte till en sträng. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&, int, int) | Avkodar en buffert av byte till en sträng. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>, int, int) | Avkodar en buffert av byte till en sträng. |
| [set_DecoderFallback](./set_decoderfallback/)(const DecoderFallbackPtr\&) | Ställer in avkodningsfallback. |
| [set_EncoderFallback](./set_encoderfallback/)(const EncoderFallbackPtr\&) | Ställer in kodningsfallback. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Standardvärde för kodsida. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
