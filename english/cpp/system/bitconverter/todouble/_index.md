---
title: System::BitConverter::ToDouble method
linktitle: ToDouble
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter::ToDouble method. Converts eight bytes from the specified array starting at the specified index to double-precision floating point value in C++.'
type: docs
weight: 700
url: /cpp/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts eight bytes from the specified array starting at the specified index to double-precision floating point value.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

Double-precision floating-point value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts eight bytes from the specified array starting at the specified index to double-precision floating point value.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<uint8_t\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

Double-precision floating-point value resulting from conversion

## See Also

* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
