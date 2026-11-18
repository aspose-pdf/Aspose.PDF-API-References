---
title: System::Text::Json::JsonReaderHelper class
linktitle: JsonReaderHelper
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonReaderHelper class in C++.'
type: docs
weight: 1500
url: /cpp/system.text.json/jsonreaderhelper/
---
## JsonReaderHelper class




```cpp
class JsonReaderHelper
```

## Methods

| Method | Description |
| --- | --- |
| static [AppendEscapedPropertyName](./appendescapedpropertyname/)(ValueStringBuilder\&, String) |  |
| static [AppendEscapedPropertyName](./appendescapedpropertyname/)(System::SharedPtr\<StringBuilder\>, String) |  |
| static [ContainsSpecialCharacters](./containsspecialcharacters/)(ReadOnlySpan\<char16_t\>) |  |
| static [CountNewLines](./countnewlines/)(ReadOnlySpan\<uint8_t\>) |  |
| static [GetTextFromUtf8](./gettextfromutf8/)(ReadOnlySpan\<uint8_t\>) |  |
| static [GetUnescaped](./getunescaped/)(ReadOnlySpan\<uint8_t\>) |  |
| static [GetUnescapedString](./getunescapedstring/)(ReadOnlySpan\<uint8_t\>) |  |
| static [GetUtf8ByteCount](./getutf8bytecount/)(ReadOnlySpan\<char16_t\>) |  |
| static [GetUtf8FromText](./getutf8fromtext/)(ReadOnlySpan\<char16_t\>, Span\<uint8_t\>) |  |
| static [IndexOfFirstNonWhiteSpace](./indexoffirstnonwhitespace/)(ReadOnlySpan\<uint8_t\>) |  |
| static [IndexOfQuoteOrAnyControlOrBackSlash](./indexofquoteoranycontrolorbackslash/)(ReadOnlySpan\<uint8_t\>) |  |
| static [IsHexDigit](./ishexdigit/)(uint8_t) |  |
| static [IsTokenTypePrimitive](./istokentypeprimitive/)(JsonTokenType) |  |
| [JsonReaderHelper](./jsonreaderhelper/)() |  |
| static [ToValueKind](./tovaluekind/)(JsonTokenType) |  |
| static [TranscodeHelper](./transcodehelper/)(ReadOnlySpan\<uint8_t\>) |  |
| static [TranscodeHelper](./transcodehelper/)(ReadOnlySpan\<uint8_t\>, Span\<char16_t\>) |  |
| static [TryDecodeBase64](./trydecodebase64/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Array\<uint8_t\>\>\&) |  |
| static [TryDecodeBase64InPlace](./trydecodebase64inplace/)(Span\<uint8_t\>, System::SharedPtr\<Array\<uint8_t\>\>\&) |  |
| static [TryGetEscapedDateTime](./trygetescapeddatetime/)(ReadOnlySpan\<uint8_t\>, DateTime\&) |  |
| static [TryGetEscapedDateTimeOffset](./trygetescapeddatetimeoffset/)(ReadOnlySpan\<uint8_t\>, DateTimeOffset\&) |  |
| static [TryGetEscapedGuid](./trygetescapedguid/)(ReadOnlySpan\<uint8_t\>, Guid\&) |  |
| static [TryGetFloatingPointConstant](./trygetfloatingpointconstant/)(ReadOnlySpan\<uint8_t\>, float\&) |  |
| static [TryGetFloatingPointConstant](./trygetfloatingpointconstant/)(ReadOnlySpan\<uint8_t\>, double\&) |  |
| static [TryGetUnescapedBase64Bytes](./trygetunescapedbase64bytes/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Array\<uint8_t\>\>\&) |  |
| static [TryGetValue](./trygetvalue/)(ReadOnlySpan\<uint8_t\>, bool, DateTime\&) |  |
| static [TryGetValue](./trygetvalue/)(ReadOnlySpan\<uint8_t\>, bool, DateTimeOffset\&) |  |
| static [TryGetValue](./trygetvalue/)(ReadOnlySpan\<uint8_t\>, bool, Guid\&) |  |
| static [TryUnescape](./tryunescape/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t\&) |  |
| static [Unescape](./unescape/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t\&) |  |
| static [Unescape](./unescape/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t, int32_t\&) |  |
| static [UnescapeAndCompare](./unescapeandcompare/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [UnescapeAndCompare](./unescapeandcompare/)(Buffers::ReadOnlySequence\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [UnescapeAndCompareBothInputs](./unescapeandcomparebothinputs/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [ValidateUtf8](./validateutf8/)(ReadOnlySpan\<uint8_t\>) |  |
## See Also

* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
