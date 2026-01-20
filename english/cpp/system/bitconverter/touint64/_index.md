---
title: System::BitConverter::ToUInt64 method
linktitle: ToUInt64
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter::ToUInt64 method. Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value in C++.'
type: docs
weight: 1500
url: /cpp/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

Unsigned 64-bit integer value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<uint8_t\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

Unsigned 64-bit integer value resulting from conversion

## See Also

* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
