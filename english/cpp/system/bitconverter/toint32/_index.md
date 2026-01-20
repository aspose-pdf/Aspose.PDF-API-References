---
title: System::BitConverter::ToInt32 method
linktitle: ToInt32
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter::ToInt32 method. Converts four bytes from the specified array starting at the specified index to 32-bit integer value in C++.'
type: docs
weight: 900
url: /cpp/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to 32-bit integer value.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

32-bit integer value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts four bytes from the specified array starting at the specified index to 32-bit integer value.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<uint8_t\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

32-bit integer value resulting from conversion

## See Also

* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
