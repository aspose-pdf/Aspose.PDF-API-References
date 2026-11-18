---
title: System::Text::Json::JsonDocument class
linktitle: JsonDocument
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonDocument class in C++.'
type: docs
weight: 600
url: /cpp/system.text.json/jsondocument/
---
## JsonDocument class




```cpp
class JsonDocument : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_RootElement](./get_rootelement/)() |  |
| static [Parse](./parse/)(ReadOnlyMemory\<uint8_t\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(Buffers::ReadOnlySequence\<uint8_t\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(System::SharedPtr\<IO::Stream\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(ReadOnlyMemory\<char16_t\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(String, JsonDocumentOptions) |  |
| static [ParseValue](./parsevalue/)(Utf8JsonReader\&) |  |
| static [TryParseValue](./tryparsevalue/)(Utf8JsonReader\&, System::SharedPtr\<JsonDocument\>\&) |  |
| [WriteTo](./writeto/)(System::SharedPtr\<Utf8JsonWriter\>) |  |
| virtual [~JsonDocument](./~jsondocument/)() |  |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
