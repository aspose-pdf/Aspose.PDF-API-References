---
title: System::Char class
linktitle: Char
second_title: Aspose.PDF for C++ API Reference
description: 'System::Char class. Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 1200
url: /cpp/system/char/
---
## Char class


Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## Methods

| Method | Description |
| --- | --- |
| static [ConvertFromUtf32](./convertfromutf32/)(uint32_t) | Converts UTF-32 code unit into an instance of [System::String](../string/) class. |
| static [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Converts the specified UTF-16 surrogate pair into UTF-32 code unit. |
| static [ConvertToUtf32](./converttoutf32/)(const String\&, int) | Converts the value of a UTF-16 encoded character or surrogate pair at a specified position in a string into UTF-32 code unit. |
| static [GetNumericValue](./getnumericvalue/)(char_t) | Converts the specified UTF-16 character into double-precision floating-point numerical value. |
| static [GetUnicodeCategory](./getunicodecategory/)(char_t) | Returns a value that represents a Unicode category of specified character. |
| static [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Determines whether the specified character is classified as a ASCII white space character. |
| static [IsControl](./iscontrol/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as Unicode control character. |
| static [IsControl](./iscontrol/)(char_t) | Determines whether the specified character is classified as Unicode control character. |
| static [IsDigit](./isdigit/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a decimal digit. |
| static [IsDigit](./isdigit/)(const String\&, const int32_t) | Determines whether the character at the specified index in the specified string is classified as a decimal digit. |
| static [IsDigit](./isdigit/)(char_t) | Determines whether the specified character is classified as a decimal digit. |
| static [IsHighSurrogate](./ishighsurrogate/)(const String\&, int) | Determines whether the character at the specified index in the specified string is UTF-16 high surrogate code unit. |
| static [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is a high surrogate. |
| static [IsHighSurrogate](./ishighsurrogate/)(char_t) | Determines whether the specified character is a high surrogate. |
| static [IsLetter](./isletter/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as Unicode letter. |
| static [IsLetter](./isletter/)(char_t) | Determines whether the specified character is classified as Unicode letter. |
| static [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as Unicode letter or a decimal digit. |
| static [IsLetterOrDigit](./isletterordigit/)(char_t) | Determines whether the specified character is classified as Unicode letter or a decimal digit. |
| static [IsLower](./islower/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a lower case letter. |
| static [IsLower](./islower/)(char_t) | Determines whether the specified character is classified as a lower case letter. |
| static [IsLower](./islower/)(const String\&, int) | Determines whether the character at the specified index in the specified string is classified as a lower case letter. |
| static [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is a low surrogate. |
| static [IsLowSurrogate](./islowsurrogate/)(char_t) | Determines whether the specified character is a low surrogate. |
| static [IsNumber](./isnumber/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a number. |
| static [IsNumber](./isnumber/)(char_t) | Determines whether the specified character is classified as a number. |
| static [IsPunctuation](./ispunctuation/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a punctuation character. |
| static [IsPunctuation](./ispunctuation/)(char_t) | Determines whether the specified character is classified as a punctuation character. |
| static [IsSeparator](./isseparator/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a separator character. |
| static [IsSeparator](./isseparator/)(char_t) | Determines whether the specified character is classified as a separator character. |
| static [IsSurrogate](./issurrogate/)(char_t) | Determines if the specified character is a UTF-16 surrogate code unit. |
| static [IsSurrogate](./issurrogate/)(const String\&, int) | Determines whether the character at the specified index in the specified string is UTF-16 surrogate code unit. |
| static [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Determines whether the two specified characters for a UTF-16 surrogate pair. |
| static [IsSurrogatePair](./issurrogatepair/)(const String\&, int) | Determines whether two consequent characters in the specified character buffer are a surrogate pair. |
| static [IsSymbol](./issymbol/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a symbol character. |
| static [IsSymbol](./issymbol/)(char_t) | Determines whether the specified character is classified as a symbol character. |
| static [IsUpper](./isupper/)(const String\&, int) | Determines whether the character at the specified index in the specified string is classified as an upper case letter. |
| static [IsUpper](./isupper/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as an upper case letter. |
| static [IsUpper](./isupper/)(char_t) | Determines whether the specified character is classified as an upper case letter. |
| static [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a white space character. |
| static [IsWhiteSpace](./iswhitespace/)(char_t) | Determines whether the specified character is classified as a white space character. |
| static [IsWhiteSpace](./iswhitespace/)(const String\&, int) | Determines whether the character at the specified index in the specified string is classified as a white space character. |
| static [Parse](./parse/)(const String\&) | Converts the first and the only character of the specified string to a char_t value. |
| static [ToLower](./tolower/)(char_t) | Converts the specified character to lower case. |
| static [ToLower](./tolower/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Converts the specified character to lower case. |
| static [ToLowerInvariant](./tolowerinvariant/)(char_t) | Converts the specified character to lower case. |
| static [ToUpper](./toupper/)(char_t) | Converts the specified character to upper case. |
| static [ToUpper](./toupper/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Converts the specified character to upper case. |
| static [ToUpperInvariant](./toupperinvariant/)(char_t) | Converts the specified character to upper case. |
| static [TryParse](./tryparse/)(const System::String\&, char_t\&) | Tries to convert a string consisting of a single character into UTF-16 character. The function succeeds only when input string is not null and has length of exactly one character. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
