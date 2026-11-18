---
title: System::Buffers::StandardFormat class
linktitle: StandardFormat
second_title: Aspose.PDF for C++ API Reference
description: 'System::Buffers::StandardFormat class. Represents a standard format specifier with an optional precision. It wraps a format symbol (a single character, e.g. ''D'', ''X'', ''O'', or ''\0'' for the default format) and an optional precision in the range [0, 99]. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 1000
url: /cpp/system.buffers/standardformat/
---
## StandardFormat class


Represents a standard format specifier with an optional precision. It wraps a format symbol (a single character, e.g. 'D', 'X', 'O', or '\0' for the default format) and an optional precision in the range [0, 99]. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class StandardFormat : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(const StandardFormat\&) const | Determines whether the current instance is equal to the specified one. |
| [get_Format](./get_format/)() const | Gets the standard format symbol. |
| [get_IsDefault](./get_isdefault/)() const | Determines whether this instance represents the default format. |
| [get_Precision](./get_precision/)() const | Gets the precision (number of digits) for this format, or NoPrecision if none. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current [StandardFormat](./). |
| [StandardFormat](./standardformat/)() | Constructs a default [StandardFormat](./) that represents the default format. |
| explicit [StandardFormat](./standardformat/)(char_t) | Constructs a [StandardFormat](./) with the specified format symbol and no precision. |
| [StandardFormat](./standardformat/)(char_t, uint8_t) | Constructs a [StandardFormat](./) with the specified format symbol and precision. |
| [ToString](./tostring/)() const | Returns a string representation of the current [StandardFormat](./). Default format instances are represented as "default"; otherwise the representation is the format symbol optionally followed by the precision, e.g. "X", "X4", "O". |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DefaultFormatSymbol](./defaultformatsymbol/) | The symbol used to represent the default format. An instance whose Format equals this value (and whose Precision equals NoPrecision) is considered default. |
| static constexpr [NoPrecision](./noprecision/) | The maximum precision value that can be specified. A precision of this value means "no explicit precision". |
## See Also

* Namespace [System::Buffers](../)
* Library [Aspose.PDF for C++](../../)
