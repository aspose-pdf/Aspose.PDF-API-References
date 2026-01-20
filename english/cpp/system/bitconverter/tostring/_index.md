---
title: System::BitConverter::ToString method
linktitle: ToString
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter::ToString method. Converts all values of the specified byte array into their hexadecimal string representation. Case of letters to use in hexadecimal notation and separator inserted between each pair of neighbouring bytes are specified through corresponding arguments in C++.'
type: docs
weight: 1200
url: /cpp/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method


Converts all values of the specified byte array into their hexadecimal string representation. Case of letters to use in hexadecimal notation and separator inserted between each pair of neighbouring bytes are specified through corresponding arguments.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=true, const String &separator=u"-")
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| uppercase | bool | Specifies the case of letters to use in resulting hexadecimal representation |
| separator | const String\& | A string used as a separator inserted between each pair of neighbouring bytes in the resulting string |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified byte array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method


Converts values of the specified byte array into their hexadecimal string representation starting at specified index.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the specified array at which to start converting |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method


Converts a range of values of the specified byte array into their hexadecimal string representation.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the specified array at which the range of the byte array elements to convert begins |
| length | int | The length of the range the byte array elements to convert |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## See Also

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
