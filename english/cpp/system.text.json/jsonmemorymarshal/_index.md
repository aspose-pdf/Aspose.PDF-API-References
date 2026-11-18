---
title: System::Text::Json::JsonMemoryMarshal class
linktitle: JsonMemoryMarshal
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::JsonMemoryMarshal class. Byte-span marshalling helpers used by the JSON reader/writer implementation in C++.'
type: docs
weight: 1100
url: /cpp/system.text.json/jsonmemorymarshal/
---
## JsonMemoryMarshal class


Byte-span marshalling helpers used by the JSON reader/writer implementation.

```cpp
class JsonMemoryMarshal
```

## Methods

| Method | Description |
| --- | --- |
| static [Cast](./cast/)(const ReadOnlySpan\<TFrom\>\&) | Casts a read-only span of one primitive type TFrom to another primitive type TTo. |
| static [Read](./read/)(const ReadOnlySpan\<uint8_t\>\&) | Reads a value of type T from the beginning of the specified byte span. |
| static [Read](./read/)(const Span\<uint8_t\>\&) | Reads a value of type T from the beginning of the specified byte span. |
| static [Write](./write/)(const Span\<uint8_t\>\&, T\&) | Writes a value of type T to the beginning of the specified byte span. |
## See Also

* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
