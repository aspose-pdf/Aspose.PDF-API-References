---
title: "System::Char-klass"
linktitle: "Char"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Char-klass. Tillhandahåller metoder för manipulering av tecken representerade som UTF-16-kodenheter. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1300
url: /sv/cpp/system/char/
---
## Char class


Tillhandahåller metoder för manipulation av tecken representerade som UTF-16‑kodenheter. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Char
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ConvertFromUtf32](./convertfromutf32/)(uint32_t) | Konverterar en UTF-32-kodenhet till en instans av [System::String](../string/) klass. |
| static [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Konverterar det angivna UTF-16-surrogatparet till en UTF-32-kodenhet. |
| static [ConvertToUtf32](./converttoutf32/)(const String\&, int) | Konverterar värdet av ett UTF-16-kodat tecken eller surrogatpar på en specificerad position i en sträng till en UTF-32-kod enhet. |
| static [GetNumericValue](./getnumericvalue/)(char_t) | Konverterar det specificerade UTF-16-tecknet till ett dubbelprecision flyttal. |
| static [GetUnicodeCategory](./getunicodecategory/)(char_t) | Returnerar ett värde som representerar en Unicode-kategori för det specificerade tecknet. |
| static [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som ett ASCII-blanktecken. |
| static [IsControl](./iscontrol/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som ett Unicode-kontrolltecken. |
| static [IsControl](./iscontrol/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som ett Unicode-kontrolltecken. |
| static [IsDigit](./isdigit/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som en decimal­siffra. |
| static [IsDigit](./isdigit/)(const String\&, const int32_t) | Bestämmer om tecknet på den specificerade indexen i den specificerade strängen klassificeras som en decimal­siffra. |
| static [IsDigit](./isdigit/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som en decimal­siffra. |
| static [IsHighSurrogate](./ishighsurrogate/)(const String\&, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade strängen är en UTF-16 högsurrogat kodenhet. |
| static [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten är en högsurrogat. |
| static [IsHighSurrogate](./ishighsurrogate/)(char_t) | Bestämmer om det specificerade tecknet är en högsurrogat. |
| static [IsLetter](./isletter/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som en Unicode-bokstav. |
| static [IsLetter](./isletter/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som en Unicode-bokstav. |
| static [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som en Unicode-bokstav eller en decimal­siffra. |
| static [IsLetterOrDigit](./isletterordigit/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som en Unicode-bokstav eller en decimal­siffra. |
| static [IsLower](./islower/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som en gemen bokstav. |
| static [IsLower](./islower/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som en gemen bokstav. |
| static [IsLower](./islower/)(const String\&, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade strängen klassificeras som en gemen bokstav. |
| static [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten är en lågsurrogat. |
| static [IsLowSurrogate](./islowsurrogate/)(char_t) | Bestämmer om det specificerade tecknet är en lågsurrogat. |
| static [IsNumber](./isnumber/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som ett tal. |
| static [IsNumber](./isnumber/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som ett tal. |
| static [IsPunctuation](./ispunctuation/)(const char_t *, int) | Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten klassificeras som ett skiljetecken. |
| static [IsPunctuation](./ispunctuation/)(char_t) | Bestämmer om det specificerade tecknet klassificeras som ett skiljetecken. |
| static [IsSeparator](./isseparator/)(const char_t *, int) | Bestämmer om tecknet på det angivna indexet i den angivna teckenbufferten klassificeras som ett separator-tecken. |
| static [IsSeparator](./isseparator/)(char_t) | Bestämmer om det angivna tecknet klassificeras som ett separator-tecken. |
| static [IsSurrogate](./issurrogate/)(char_t) | Bestämmer om det angivna tecknet är en UTF-16 surrogat-kod-enhet. |
| static [IsSurrogate](./issurrogate/)(const String\&, int) | Bestämmer om tecknet på det angivna indexet i den angivna strängen är en UTF-16 surrogat-kod-enhet. |
| static [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Bestämmer om de två angivna tecknen för ett UTF-16 surrogatpar. |
| static [IsSurrogatePair](./issurrogatepair/)(const String\&, int) | Bestämmer om två på varandra följande tecken i den angivna teckenbufferten bildar ett surrogatpar. |
| static [IsSymbol](./issymbol/)(const char_t *, int) | Bestämmer om tecknet på det angivna indexet i den angivna teckenbufferten klassificeras som ett symbol-tecken. |
| static [IsSymbol](./issymbol/)(char_t) | Bestämmer om det angivna tecknet klassificeras som ett symbol-tecken. |
| static [IsUpper](./isupper/)(const String\&, int) | Bestämmer om tecknet på det angivna indexet i den angivna strängen klassificeras som en versal. |
| static [IsUpper](./isupper/)(const char_t *, int) | Bestämmer om tecknet på det angivna indexet i den angivna teckenbufferten klassificeras som en versal. |
| static [IsUpper](./isupper/)(char_t) | Bestämmer om det angivna tecknet klassificeras som en versal. |
| static [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Bestämmer om tecknet på det angivna indexet i den angivna teckenbufferten klassificeras som ett blanksteg-tecken. |
| static [IsWhiteSpace](./iswhitespace/)(char_t) | Bestämmer om det angivna tecknet klassificeras som ett blanksteg-tecken. |
| static [IsWhiteSpace](./iswhitespace/)(const String\&, int) | Bestämmer om tecknet på det angivna indexet i den angivna strängen klassificeras som ett blanksteg-tecken. |
| static [Parse](./parse/)(const String\&) | Konverterar det första och enda tecknet i den angivna strängen till ett char_t‑värde. |
| static [ToLower](./tolower/)(char_t) | Konverterar det angivna tecknet till gemener. |
| static [ToLower](./tolower/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Konverterar det angivna tecknet till gemener. |
| static [ToLowerInvariant](./tolowerinvariant/)(char_t) | Konverterar det angivna tecknet till gemener. |
| static [ToUpper](./toupper/)(char_t) | Konverterar det angivna tecknet till versaler. |
| static [ToUpper](./toupper/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Konverterar det angivna tecknet till versaler. |
| static [ToUpperInvariant](./toupperinvariant/)(char_t) | Konverterar det angivna tecknet till versaler. |
| static [TryParse](./tryparse/)(const System::String\&, char_t\&) | Försöker konvertera en sträng som består av ett enda tecken till ett UTF-16‑tecken. Funktionen lyckas endast när inmatningssträngen inte är null och har en längd på exakt ett tecken. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
