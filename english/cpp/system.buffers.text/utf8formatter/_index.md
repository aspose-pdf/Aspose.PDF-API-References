---
title: System::Buffers::Text::Utf8Formatter class
linktitle: Utf8Formatter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::Text::Utf8Formatter class. Provides formatting of common value types into UTF-8 encoded byte spans. Formatting is invariant-culture based in C++.'
type: docs
weight: 200
url: /cpp/system.buffers.text/utf8formatter/
---
## Utf8Formatter class


Provides formatting of common value types into UTF-8 encoded byte spans. Formatting is invariant-culture based.

```cpp
class Utf8Formatter
```

## Methods

| Method | Description |
| --- | --- |
| static [TryFormat](./tryformat/)(int32_t, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(uint32_t, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(int64_t, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(uint64_t, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(float, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(double, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(const Decimal\&, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(const Guid\&, Span\<uint8_t\>, int32_t\&) |  |
| static [TryFormat](./tryformat/)(const DateTime\&, Span\<uint8_t\>, int32_t\&, const StandardFormat\&) |  |
| static [TryFormat](./tryformat/)(const DateTimeOffset\&, Span\<uint8_t\>, int32_t\&, const StandardFormat\&) |  |
| static [TryFormat](./tryformat/)(uint8_t, Span\<uint8_t\>, int32_t\&, const StandardFormat\&) |  |
| static [TryFormat](./tryformat/)(const TimeSpan\&, Span\<uint8_t\>, int32_t\&, char_t) |  |
| static [TryFormat](./tryformat/)(const TimeSpan\&, Span\<uint8_t\>, int32_t\&, const StandardFormat\&) |  |
| [Utf8Formatter](./utf8formatter/)() |  |
## See Also

* Namespace [System::Buffers::Text](../)
* Library [Aspose.PDF for C++](../../)
