---
title: "System::String klass"
linktitle: "String"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String klass. Strängklass som används i hela biblioteket. Är en ersättare för C# System.String vid kodöversättning. Av optimeringsskäl betraktas den inte som en underklass till Object. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ i C++."
type: docs
weight: 6100
url: /sv/cpp/system/string/
---
## String class


[String](./) class used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [begin](./begin/)() const | Returnerar pekare till början av den faktiska strängbufferten. Allokerar aldrig om något. Garanterar inte att bufferten är null-terminerad. |
| [Clone](./clone/)() const | Skapar en kopia av den aktuella strängen. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, bool) | Less-equal-greater-jämför två delsträngar. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) | Less-equal-greater-jämför två delsträngar. |
| static [Compare](./compare/)(const String\&, const String\&, System::StringComparison) | Less-equal-greater-jämför två strängar. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, System::StringComparison) | Less-equal-greater-jämför två strängar. |
| static [Compare](./compare/)(const String\&, const String\&, bool) | Less-equal-greater-jämför två strängar. |
| static [Compare](./compare/)(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) | Less-equal-greater-jämför två strängar. |
| static [CompareOrdinal](./compareordinal/)(const String\&, const String\&) | Less-equal-greater-jämför två strängar med ordinalt läge. |
| static [CompareOrdinal](./compareordinal/)(const String\&, int, const String\&, int, int) | Less-equal-greater-jämför två strängar med ordinalt läge. |
| [CompareTo](./compareto/)(const String\&) const | Jämför två strängar i 'less-equals-more'-stil. Använder aktuell kultur. |
| static [Concat](./concat/)(const ArrayPtr\<String\>\&) | Konkatenar strängar. |
| static [Concat](./concat/)(const String\&, const String\&) | Konkatenar strängar. |
| static [Concat](./concat/)(const String\&, const String\&, const String\&) | Konkatenar strängar. |
| static [Concat](./concat/)(const String\&, const String\&, const String\&, const String\&) | Konkatenar strängar. |
| [Contains](./contains/)(const String\&) const | Kontrollerar om str är en delsträng av den aktuella strängen. |
| [Contains](./contains/)(char16_t) const | Kontrollerar om strängen innehåller angivet tecken. |
| static [Copy](./copy/)(const String\&) | Skapar en strängkopia. |
| [CopyTo](./copyto/)(int, const ArrayPtr\<char_t\>\&, int, int) const | Kopierar tecken från strängen till befintliga array‑element. Ingen storleksändring sker. |
| [end](./end/)() const | Returnerar pekare till slutet av den faktiska strängbufferten. Allokerar aldrig om något. Garanterar inte att bufferten är null-terminerad. |
| [EndsWith](./endswith/)(const String\&) const | Kontrollerar om strängen slutar med angiven delsträng. |
| [EndsWith](./endswith/)(const String\&, System::StringComparison) const | Kontrollerar om strängen slutar med angiven delsträng. |
| [EndsWith](./endswith/)(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Kontrollerar om strängen slutar med angiven delsträng. |
| [Equals](./equals/)(const String\&, System::StringComparison) const | [String](./) likhetsjämförelse. Flera lägen som tillhandahålls av uppräkningen [StringComparison](../stringcomparison/) stöds. |
| [Equals](./equals/)(const String\&) const | [String](./) likhetsjämförelse. Använder jämförelseläget [System::StringComparison::Ordinal](../stringcomparison/). |
| static [Equals](./equals/)(const String\&, const String\&) | Jämför två strängar med likhet med Ordinal jämförelseläge. |
| static [Equals](./equals/)(const String\&, const String\&, System::StringComparison) | Jämför två strängar med likhet. |
| [FastToAscii](./fasttoascii/)(char, int) const | Försöker konvertera en [String](./) till en ASCII-sträng. |
| static [Format](./format/)(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) | Formaterar sträng i C#-stil. |
| static [Format](./format/)(std::nullptr_t, const String\&, const Args\&...) | Formaterar sträng i C#-stil. |
| static [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formaterar sträng i C#-stil. |
| static [Format](./format/)(const String\&, const Args\&...) | Formaterar sträng i C#-stil. |
| static [Format](./format/)(const String\&, const System::ArrayPtr\<T\>\&) | Formaterar sträng i C#-stil. |
| static [FromAscii](./fromascii/)(const char *) | Skapar [String](./) från en ASCII-sträng. |
| static [FromAscii](./fromascii/)(const char *, int) | Skapar [String](./) från en ASCII-sträng. |
| static [FromAscii](./fromascii/)(const std::string\&) | Skapar [String](./) från en ASCII-sträng. |
| static [FromUtf16](./fromutf16/)(const std::u16string\&) | Skapar [String](./) från en utf16-sträng. |
| static [FromUtf32](./fromutf32/)(const uint32_t *, int32_t) | Skapar [String](./) från en utf32-sträng. |
| static [FromUtf8](./fromutf8/)(const char *) | Skapar [String](./) från en utf8-sträng. |
| static [FromUtf8](./fromutf8/)(const char *, int) | Skapar [String](./) från en utf8-sträng. |
| static [FromUtf8](./fromutf8/)(const uint8_t *) | Skapar [String](./) från en utf8-sträng. |
| static [FromUtf8](./fromutf8/)(const std::string\&) | Skapar [String](./) från en utf8-sträng. |
| static [FromWCS](./fromwcs/)(const std::wstring\&) | Skapar [String](./) från en widestring. |
| [get_Length](./get_length/)() const | Hämtar stränglängd. |
| [GetHashCode](./gethashcode/)() const | Hashar den innehållna strängen. Implementerad i ICU, matchar inte hashvärden i C#. |
| [IndexOf](./indexof/)(const String\&, System::StringComparison) const | Framåtsökning i delsträng. |
| [IndexOf](./indexof/)(char_t, int) const | Framåtsökning av tecken. |
| [IndexOf](./indexof/)(char_t, int, int) const | Framåtsökning av tecken i delsträng. |
| [IndexOf](./indexof/)(const String\&, int) const | Framåtsökning i delsträng. |
| [IndexOf](./indexof/)(const String\&, int, System::StringComparison) const | Framåtsökning i delsträng. |
| [IndexOf](./indexof/)(const String\&, int, int, System::StringComparison) const | Framåtsökning i delsträng. |
| [IndexOf](./indexof/)(const String\&, int, int) const | Framåtsökning i delsträng. |
| [IndexOfAny](./indexofany/)(char_t, int) const | Framåtsökning av tecken. |
| [IndexOfAny](./indexofany/)(const String\&, int) const | Söker därför efter alla tecken i str i detta. Om det första tecknet hittas returneras dess position, annars söks efter det andra och så vidare. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&) const | Söker efter någon av de överförda tecknen i hela strängen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan jämförs det andra och så vidare. Returnerar index för det första som matchar någon av måltecknen. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&, int32_t) const | Söker efter någon av de överförda tecknen i delsträngen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan jämförs det andra och så vidare. Returnerar index för det första som matchar någon av måltecknen. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const | Söker efter någon av de överförda tecknen i delsträngen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan jämförs det andra och så vidare. Returnerar index för det första som matchar någon av måltecknen. |
| [Insert](./insert/)(int, const String\&) const | Infogar delsträng på angiven position. |
| [Is](./is/)(const System::TypeInfo\&) const | Kontrollerar om strängobjektet är av den typ som anges av den överförda [TypeInfo](../typeinfo/). |
| [IsAsciiString](./isasciistring/)() const | Anger om en [String](./) endast innehåller ASCII-symboler. |
| [IsEmpty](./isempty/)() const | Kontrollerar om strängen både är icke-null och tom. |
| [IsNormalized](./isnormalized/)(System::Text::NormalizationForm) const | Kontrollerar om en Unicode-sträng är normaliserad med den angivna normaliseringsformen. |
| [IsNull](./isnull/)() const | Kontrollerar om strängen anses vara null. [String](./) är null endast om den konstruerats via [String()](./string/)‑konstruktorn, flyttats, kopierats eller tilldelats från en null‑sträng eller om [reset()](./reset/)‑metoden har anropats. |
| [IsNullOrEmpty](./isnullorempty/)() const | Kontrollerar om strängen är tom eller anses vara null. |
| static [IsNullOrEmpty](./isnullorempty/)(const String\&) | Kontrollerar om den överförda strängen är null eller tom. |
| static [IsNullOrWhiteSpace](./isnullorwhitespace/)(const String\&) | Anger om en specificerad sträng är null, tom eller endast består av blankstegstecken. |
| static [Join](./join/)(const String\&, const ArrayPtr\<String\>\&, int, int) | Sammanfogar en array med strängen som avgränsare. |
| static [Join](./join/)(const String\&, const System::Details::ArrayView\<String\>\&, int, int) | Sammanfogar en array med strängen som avgränsare. |
| static [Join](./join/)(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) | Sammanfogar en array med strängen som avgränsare. |
| static [Join](./join/)(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) | Sammanfogar en array med strängen som avgränsare. |
| [LastIndexOf](./lastindexof/)(const String\&, int) const | Sökning bakåt i delsträng. |
| [LastIndexOf](./lastindexof/)(const String\&, System::StringComparison) const | Sökning bakåt i delsträng. |
| [LastIndexOf](./lastindexof/)(const String\&, int, System::StringComparison) const | Sökning bakåt i delsträng. |
| [LastIndexOf](./lastindexof/)(const String\&, int, int, StringComparison) const | Sökning bakåt i delsträng. |
| [LastIndexOf](./lastindexof/)(char_t) const | Sökning bakåt i tecken. |
| [LastIndexOf](./lastindexof/)(char_t, int32_t) const | Sökning bakåt i tecken. |
| [LastIndexOf](./lastindexof/)(char_t, int32_t, int32_t) const | Sökning bakåt i tecken. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&) const | Söker efter någon av de överförda tecknen i hela strängen baklänges. Jämför sista tecken i strängen med alla tecken i anyOf, sedan föregående tecken och så vidare. Returnerar index för den första matchen som hittas. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&, int32_t) const | Söker efter någon av de överförda tecknen i delsträngen baklänges. Jämför sista tecken i strängen med alla tecken i anyOf, sedan föregående tecken och så vidare. Returnerar index för den första matchen som hittas. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const | Söker efter någon av de överförda tecknen i delsträngen baklänges. Jämför sista tecken i strängen med alla tecken i anyOf, sedan föregående tecken och så vidare. Returnerar index för den första matchen som hittas. |
| [Normalize](./normalize/)(System::Text::NormalizationForm) const | Normaliserar Unicode-sträng med den angivna normaliseringsformen. |
| [operator ReadOnlySpan< char16_t >](./operatorreadonlyspan_char16_t_/)() const | Konverterar strängen till ett skrivskyddat span. |
| [operator!=](./operator!=/)(const String\&) const | Icke‑likhetsoperator. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Kontrollerar om strängen inte är null. Använder samma logik som anropet [IsNull()](./isnull/). |
| [operator+](./operator+/)(const String\&) const | [String](./) sammanslagningsoperator. |
| [operator+](./operator+/)(const T\&) const | [String](./) sammanslagning med strängliteral eller teckensträngspointer. |
| [operator+](./operator+/)(char_t) const | Lägger till ett tecken i slutet av strängen. |
| [operator+](./operator+/)(int) const | Lägger till heltalsvärdets strängrepresentation i slutet av strängen. |
| [operator+](./operator+/)(uint32_t) const | Lägger till det osignerade heltalsvärdets strängrepresentation i slutet av strängen. |
| [operator+](./operator+/)(double) const | Lägger till flyttalsvärdets strängrepresentation i slutet av strängen. |
| [operator+](./operator+/)(int64_t) const | Lägger till heltalsvärdets strängrepresentation i slutet av strängen. |
| [operator+](./operator+/)(const T\&) const | Lägger till referenstypobjektets strängrepresentation i slutet av strängen. |
| [operator+](./operator+/)(const T\&) const | Lägger till referenstypobjektets strängrepresentation i slutet av strängen. |
| [operator+](./operator+/)(T) const | Lägger till booleskt värdes strängrepresentation i slutet av strängen. |
| [operator+=](./operator+=/)(char_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(const String\&) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(double) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(uint8_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(int16_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(uint16_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(int32_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(uint32_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(int64_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(uint64_t) | Sammanslagningstilldelningsoperator. |
| [operator+=](./operator+=/)(T) | Sammanslagningstilldelningsoperator. |
| [operator<](./operator_/)(const String\&) const | Jämför strängar i ordning. |
| [operator=](./operator=/)(const String\&) | Tilldelningsoperator. |
| [operator=](./operator=/)(String\&&) | Flyttilldelningsoperator. |
| [operator==](./operator==/)(const String\&) const | Likhetsoperator. |
| [operator==](./operator==/)(std::nullptr_t) const | Kontrollerar om strängen är null. Tillämpar samma logik som [IsNull()](./isnull/) anrop. |
| [operator>](./operator_/)(const String\&) const | Jämför strängar i ordning. |
| [operator[]](./operator[]/)(int) const | Hämtar tecken på angiven position. |
| [PadLeft](./padleft/)(int, char_t) const | Lägger till utfyllnad till vänster om originalsträngen. |
| [PadRight](./padright/)(int, char_t) const | Lägger till utfyllnad till höger om originalsträngen. |
| [rbegin](./rbegin/)() const | Returnerar omvänd iterator till det sista tecknet (om något) i den faktiska strängbufferten. |
| [Remove](./remove/)(int32_t, int32_t) const | Extraherar allt utom delsträngen från den aktuella strängen. |
| [rend](./rend/)() const | Returnerar omvänd iterator till före det första tecknet (om något) i den faktiska strängbufferten. |
| [Replace](./replace/)(char_t, char_t) const | Ersätter alla förekomster av tecknet i strängen. |
| [Replace](./replace/)(const String\&, const String\&) const | Ersätter alla förekomster av sökningen i denna sträng. |
| [reset](./reset/)() | Sätter strängen till null. Är analogt med 'string_variable_name = null' i C#. |
| [SetCharAt](./setcharat/)(int, char_t) | Sätter tecken på angiven position. |
| [Split](./split/)(char_t, StringSplitOptions) const | Delar strängen efter tecken. |
| [Split](./split/)(char_t, int32_t, StringSplitOptions) const | Delar strängen efter tecken. |
| [Split](./split/)(char_t, char_t, StringSplitOptions) const | Delar strängen efter ett av två tecken. |
| [Split](./split/)(const ArrayPtr\<char_t\>\&, StringSplitOptions) const | Delar strängen efter ett av de angivna tecknen. |
| [Split](./split/)(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const | Delar strängen efter ett av de angivna tecknen. |
| [Split](./split/)(const String\&, StringSplitOptions) const | Delar strängen efter delsträng. |
| [Split](./split/)(const String\&, int, StringSplitOptions) const | Delar strängen efter delsträng. |
| [Split](./split/)(const ArrayPtr\<String\>\&, StringSplitOptions) const | Delar strängen efter delsträng. |
| [Split](./split/)(const ArrayPtr\<String\>\&, int, StringSplitOptions) const | Delar strängen efter delsträng. För närvarande stöds endast separatorarray med noll eller ett element. |
| [StartsWith](./startswith/)(const String\&) const | Kontrollerar om strängen börjar med den angivna delsträngen. |
| [StartsWith](./startswith/)(const String\&, System::StringComparison) const | Kontrollerar om strängen börjar med den angivna delsträngen. |
| [StartsWith](./startswith/)(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Kontrollerar om strängen börjar med den angivna delsträngen. |
| [String](./string/)() | Standardkonstruktor. Skapar ett strängobjekt som betraktas som null. |
| [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) | Konstruerar en sträng baserat på en strängliteral. Betraktar litteralen som en nullterminerad sträng, beräknar målsträngens längd baserat på litteralens storlek. |
| [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) | Konstruerar en sträng baserat på en teckensträngspekare. Behandlar den pekade strängen som nullterminerad, beräknar målsträngens längd baserat på nulltecknet. |
| explicit [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) | Konstruerar en sträng baserat på en strängliteral. Betraktar litteralen som en nullterminerad sträng i UTF‑8, beräknar målsträngens längd baserat på litteralens storlek. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) | Konstruerar en sträng baserat på en teckensträngspekare. Behandlar den pekade strängen som nullterminerad i UTF‑8, beräknar målsträngens längd baserat på nulltecknet. |
| [String](./string/)(const char16_t *, int) | Konstruerar en sträng från en teckensträngspekare och explicit längd. |
| [String](./string/)(const ReadOnlySpan\<char16_t\>\&) | Initierar en ny instans av klassen [System.String](./) till Unicode-tecknen som anges i det specificerade skrivskyddade intervallet. |
| [String](./string/)(const char *, int) | Konstruerar en sträng från en teckensträngspekare och explicit längd. |
| [String](./string/)(const char16_t *, int, int) | Konstruerar en sträng från en teckensträngspekare från startposition med angiven längd. |
| explicit [String](./string/)(const char16_t, int) | Fyllkonstruktor. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr-konstruktor. Deklarerad som mall för att lösa prioriteringar med andra mallkonstruktorer. |
| explicit [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) | Skapar en sträng baserad på widestring-literal. Betraktar litteralen som en nullterminerad sträng, beräknar målsträngens längd baserat på litteralens storlek. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) | Skapar en sträng baserad på pekare till widecharacter-sträng. Behandlar den pekade strängen som nullterminerad, beräknar målsträngens längd baserat på nulltecknet. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| explicit [String](./string/)(const wchar_t *, int) | Skapar en sträng från pekare till widecharacter-sträng och explicit längd. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| explicit [String](./string/)(const wchar_t, int) | Fyllkonstruktor. Konvertering från wchar_t är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| [String](./string/)(const String\&) | Kopieringskonstruktor. |
| [String](./string/)(String\&&) | Flyttkonstruktor. |
| [String](./string/)(const ArrayPtr\<char16_t\>\&) | Konverterar hela teckenarrayen till en sträng. |
| [String](./string/)(const ArrayPtr\<char16_t\>\&, int, int) | Konverterar ett delintervall av teckenarrayen till en sträng. Om parametrarna ligger utanför arrayens gränser, skapas en tom sträng. |
| explicit [String](./string/)(const codeporting_icu::UnicodeString\&) | Omsluter UnicodeString i [String](./). |
| explicit [String](./string/)(codeporting_icu::UnicodeString\&&) | Flyttkonstruktor. |
| explicit [String](./string/)(const std::wstring\&) | Skapar [String](./) från en widestring. |
| explicit [String](./string/)(const std::u16string\&) | Skapar [String](./) från en utf16-sträng. |
| explicit [String](./string/)(const std::string\&) | Skapar [String](./) från std::string‑sträng presenterad i UTF‑8‑format. |
| explicit [String](./string/)(const std::u32string\&) | Skapar [String](./) från std::u32string‑sträng. |
| [Substring](./substring/)(int32_t) const | Extraherar delsträng. |
| [Substring](./substring/)(int32_t, int32_t) const | Extraherar delsträng. |
| [ToAsciiString](./toasciistring/)() const | Konverterar sträng till std::string. Använder ASCII‑kodning. |
| [ToByteArray](./tobytearray/)(int32_t, int32_t, bool) const | Konverterar sträng eller delsträng till en bytearray. |
| [ToCharArray](./tochararray/)(int32_t, int32_t) const | Konverterar sträng eller delsträng till en teckenarray. |
| [ToLower](./tolower/)() const | Konverterar alla tecken i strängen till gemener. |
| [ToLower](./tolower/)(const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Konverterar alla tecken i strängen till gemener med specifik kultur. |
| [ToLowerInvariant](./tolowerinvariant/)() const | Konverterar alla tecken i strängen till gemener med invariant kultur. |
| [ToString](./tostring/)() const | Omslag för att hantera [String](./)-klassen i sammanhang där [ToString()](./tostring/) anropas på värdetypobjekt. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Omslag för att hantera [String](./)-klassen i sammanhang där [ToString()](./tostring/) anropas på värdetypobjekt. |
| [ToU16Str](./tou16str/)() const | Konverterar sträng till std::u16string. |
| [ToU32Str](./tou32str/)() const | Konverterar sträng till std::u32string. |
| [ToUpper](./toupper/)() const | Konverterar alla tecken i strängen till versaler. |
| [ToUpper](./toupper/)(const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Konverterar alla tecken i strängen till versaler med specifik kultur. |
| [ToUpperInvariant](./toupperinvariant/)() const | Konverterar alla tecken i strängen till versaler med invariant kultur. |
| [ToUtf8String](./toutf8string/)() const | Konverterar sträng till std::string. Använder UTF‑8‑kodning. |
| [ToWCS](./towcs/)() const | Konverterar sträng till std::wstring. |
| [Trim](./trim/)() const | Tar bort alla blankstegstecken från både början och slutet av strängen. |
| [Trim](./trim/)(char_t) const | Tar bort alla förekomster av det angivna tecknet från både början och slutet av strängen. |
| [Trim](./trim/)(const String\&) const | Tar bort alla förekomster av de angivna tecknen från både början och slutet av strängen. |
| [Trim](./trim/)(const ArrayPtr\<char_t\>\&) const | Tar bort alla förekomster av de angivna tecknen från både början och slutet av strängen. |
| [TrimEnd](./trimend/)() const | Tar bort alla blankstegstecken från slutet av strängen. |
| [TrimEnd](./trimend/)(char_t) const | Tar bort alla förekomster av det angivna tecknet från slutet av strängen. |
| [TrimEnd](./trimend/)(const String\&) const | Tar bort alla förekomster av de angivna tecknen från slutet av strängen. |
| [TrimEnd](./trimend/)(const ArrayPtr\<char_t\>\&) const | Tar bort alla förekomster av de angivna tecknen från slutet av strängen. |
| [TrimStart](./trimstart/)() const | Tar bort alla blankstegstecken från början av strängen. |
| [TrimStart](./trimstart/)(char_t) const | Tar bort alla förekomster av det angivna tecknet från början av strängen. |
| [TrimStart](./trimstart/)(const String\&) const | Tar bort alla förekomster av de angivna tecknen från början av strängen. |
| [TrimStart](./trimstart/)(const ArrayPtr\<char_t\>\&) const | Tar bort alla förekomster av de angivna tecknen från början av strängen. |
| [u_str](./u_str/)() const | Returnerar en ICU‑stil nullterminerad buffert. Kan omallokera strängen. |
| [~String](./~string/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | Tom sträng. |
| static [Null](./null/) | Nullsträng. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
## Anmärkningar



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Konstruera en sträng från teckenarrayen och skriv ut den.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Konstruera en sträng från bytearrayen och skriv ut den.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Trimma strängen nedan och skriv ut den.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Skriv ut antalet ord i .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
This code example produces the following output:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
