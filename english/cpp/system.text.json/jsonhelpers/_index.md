---
title: System::Text::Json::JsonHelpers class
linktitle: JsonHelpers
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonHelpers class in C++.'
type: docs
weight: 1000
url: /cpp/system.text.json/jsonhelpers/
---
## JsonHelpers class




```cpp
class JsonHelpers
```

## Methods

| Method | Description |
| --- | --- |
| static [AreEqualJsonNumbers](./areequaljsonnumbers/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [CreateDictionaryFromCollection](./createdictionaryfromcollection/)(System::SharedPtr\<Collections::Generic::IEnumerable\<Collections::Generic::KeyValuePair\<TKey, TValue\>\>\>, System::SharedPtr\<Collections::Generic::IEqualityComparer\<TKey\>\>) |  |
| static [EscapeValue](./escapevalue/)(ReadOnlySpan\<uint8_t\>, int32_t, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>) |  |
| static [get_IntegerRegex](./get_integerregex/)() |  |
| static [GetEscapedPropertyNameSection](./getescapedpropertynamesection/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>) |  |
| static [GetUnescapedSpan](./getunescapedspan/)(Utf8JsonReader\&) |  |
| static [IsDigit](./isdigit/)(uint8_t) |  |
| static [IsInRangeInclusive](./isinrangeinclusive/)(uint32_t, uint32_t, uint32_t) |  |
| static [IsInRangeInclusive](./isinrangeinclusive/)(int32_t, int32_t, int32_t) |  |
| static [IsInRangeInclusive](./isinrangeinclusive/)(int64_t, int64_t, int64_t) |  |
| static [IsInRangeInclusive](./isinrangeinclusive/)(JsonTokenType, JsonTokenType, JsonTokenType) |  |
| static [IsValidDateTimeOffsetParseLength](./isvaliddatetimeoffsetparselength/)(int32_t) |  |
| static [IsValidUnescapedDateTimeOffsetParseLength](./isvalidunescapeddatetimeoffsetparselength/)(int32_t) |  |
| [JsonHelpers](./jsonhelpers/)() |  |
| static [ReadWithVerify](./readwithverify/)(Utf8JsonReader\&) |  |
| static [RequiresSpecialNumberHandlingOnWrite](./requiresspecialnumberhandlingonwrite/)(Nullable\<Serialization::JsonNumberHandling\>) |  |
| static [SkipWithVerify](./skipwithverify/)(Utf8JsonReader\&) |  |
| static [StableSortByKey](./stablesortbykey/)(System::SharedPtr\<Collections::Generic::List\<T\>\>, Func\<T, TKey\>) |  |
| static [TraverseGraphWithTopologicalSort](./traversegraphwithtopologicalsort/)(T, Func\<T, System::SharedPtr\<Collections::Generic::ICollection\<T\>\>\>, System::SharedPtr\<Collections::Generic::IEqualityComparer\<T\>\>) |  |
| static [TryAdvanceWithOptionalReadAhead](./tryadvancewithoptionalreadahead/)(Utf8JsonReader\&, bool) |  |
| static [TryLookupUtf8Key](./trylookuputf8key/)(System::SharedPtr\<Collections::Generic::Dictionary\<String, TValue\>\>, ReadOnlySpan\<uint8_t\>, TValue\&) |  |
| static [TryParseAsISO](./tryparseasiso/)(ReadOnlySpan\<uint8_t\>, DateTime\&) |  |
| static [TryParseAsISO](./tryparseasiso/)(ReadOnlySpan\<uint8_t\>, DateTimeOffset\&) |  |
| static [TrySkipPartial](./tryskippartial/)(Utf8JsonReader\&) |  |
| static [ValidateInt32MaxArrayLength](./validateint32maxarraylength/)(uint32_t) |  |
## See Also

* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
