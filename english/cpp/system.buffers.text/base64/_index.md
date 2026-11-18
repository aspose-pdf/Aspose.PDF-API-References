---
title: System::Buffers::Text::Base64 class
linktitle: Base64
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::Text::Base64 class. Provides methods for converting between binary data and UTF-8 encoded text in base-64 format in C++.'
type: docs
weight: 100
url: /cpp/system.buffers.text/base64/
---
## Base64 class


Provides methods for converting between binary data and UTF-8 encoded text in base-64 format.

```cpp
class Base64
```

## Methods

| Method | Description |
| --- | --- |
| static [DecodeFromUtf8](./decodefromutf8/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t\&, int32_t\&) | Decodes UTF-8 encoded base-64 text into a span of bytes. |
| static [DecodeFromUtf8InPlace](./decodefromutf8inplace/)(Span\<uint8_t\>, int32_t\&) | Decodes UTF-8 encoded base-64 text in place. |
| static [EncodeToUtf8](./encodetoutf8/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t\&, int32_t\&) | Encodes the span of bytes into UTF-8 encoded base-64 text. |
| static [GetMaxDecodedFromUtf8Length](./getmaxdecodedfromutf8length/)(int32_t) | Gets the maximum number of bytes produced by decoding the specified number of UTF-8 base-64 bytes. |
| static [GetMaxEncodedToUtf8Length](./getmaxencodedtoutf8length/)(int32_t) | Gets the maximum number of UTF-8 bytes produced by encoding the specified number of bytes. |
## See Also

* Namespace [System::Buffers::Text](../)
* Library [Aspose.PDF for C++](../../)
