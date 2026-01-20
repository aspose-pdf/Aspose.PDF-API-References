---
title: System::BitConverter::ToSingle method
linktitle: ToSingle
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter::ToSingle method. Converts four bytes from the specified array starting at the specified index to single-precision floating point value in C++.'
type: docs
weight: 1100
url: /cpp/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to single-precision floating point value.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

Single-precision floating-point value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to single-precision floating point value.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<uint8_t\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

Single-precision floating-point value resulting from conversion

## See Also

* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
