---
title: System::BitConverter::ToChar method
linktitle: ToChar
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter::ToChar method. Converts two bytes from the specified array starting at the specified index to char_t value in C++.'
type: docs
weight: 600
url: /cpp/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) method


Converts two bytes from the specified array starting at the specified index to char_t value.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

char_t value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) method


Converts two bytes from the specified array starting at the specified index to char_t value.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<uint8_t\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### ReturnValue

char_t value resulting from conversion

## See Also

* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
