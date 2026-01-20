---
title: System::Collections::Specialized::BitVector32 class
linktitle: BitVector32
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Specialized::BitVector32 class. Provides a simple light bit vector with easy integer or Boolean access to a 32 bit storage in C++.'
type: docs
weight: 100
url: /cpp/system.collections.specialized/bitvector32/
---
## BitVector32 class


Provides a simple light bit vector with easy integer or [Boolean](../../system/boolean/) access to a 32 bit storage.

```cpp
class BitVector32
```

## Nested classes

* Class [Section](./section/)
## Methods

| Method | Description |
| --- | --- |
| [BitVector32](./bitvector32/)() | Initializes a new empty instance of the [BitVector32](./). |
| [BitVector32](./bitvector32/)(int32_t) | Initializes a new instance of the [BitVector32](./) structure with the specified internal data. |
| [BitVector32](./bitvector32/)(const BitVector32\&) | Initializes a new instance of the [BitVector32](./) structure with the information in the specified value. |
| static [CreateMask](./createmask/)() | Creates the first mask in a series. |
| static [CreateMask](./createmask/)(int32_t) | Creates the next mask in a series. |
| static [CreateSection](./createsection/)(int16_t) | Creates the first section in a series, with the specified maximum value. |
| static [CreateSection](./createsection/)(int16_t, BitVector32::Section) | Creates the next section in a series, with the specified maximum value. |
| [Equals](./equals/)(const BitVector32\&) | Determines whether the specified object is the same as the current. |
| [get_Data](./get_data/)() | returns the raw data stored in this bit vector... |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [idx_get](./idx_get/)(int32_t) | Gets a value indicating whether all the specified bits are set. |
| [idx_get](./idx_get/)(BitVector32::Section) | Gets the value for the specified section. |
| [idx_set](./idx_set/)(int32_t, bool) | Sets a value indicating whether all the specified bits are set. |
| [idx_set](./idx_set/)(BitVector32::Section, int32_t) | Sets the value for the specified section. |
| static [ToString](./tostring/)(const BitVector32\&) | Converts value represented by value parameter to string. |
| [ToString](./tostring/)() const | Converts value represented by current object to string. |
## See Also

* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
