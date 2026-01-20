---
title: System::Int32 class
linktitle: Int32
second_title: Aspose.PDF for C++ API Reference
description: 'System::Int32 class. Contains methods to work with the 32-bit integer in C++.'
type: docs
weight: 4100
url: /cpp/system/int32/
---
## Int32 class


Contains methods to work with the 32-bit integer.

```cpp
class Int32
```

## Methods

| Method | Description |
| --- | --- |
| static [Parse](./parse/)(const String\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer using the provided formatting information. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer using the provided formatting information and number style. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, std::nullptr_t) |  |
| static [Parse](./parse/)(const ReadOnlySpan\<char16_t\>\&) |  |
| static [Parse](./parse/)(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) |  |
| static [Parse](./parse/)(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) |  |
| static [TryParse](./tryparse/)(const String\&, int32_t\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer using the provided formatting information and number style. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) |  |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) |  |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Largest possible value. |
| static constexpr [MinValue](./minvalue/) | Smallest possible value. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
