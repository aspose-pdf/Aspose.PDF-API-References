---
title: System::Xml::XmlNameTable::Get method
linktitle: Get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNameTable::Get method. When overridden in a derived class, gets the atomized string containing the same characters as the specified range of characters in the given array in C++.'
type: docs
weight: 200
url: /cpp/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


When overridden in a derived class, gets the atomized string containing the same characters as the specified range of characters in the given array.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const ArrayPtr\<char16_t\>\& | The character array containing the name to look up. |
| offset | int32_t | The zero-based index into the array specifying the first character of the name. |
| length | int32_t | The number of characters in the name. |

### ReturnValue

The atomized string or **nullptr** if the string has not already been atomized. If **length** is zero, [String::Empty](../../../system/string/empty/) is returned.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Get(const String\&) method


When overridden in a derived class, gets the atomized string containing the same value as the specified string.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const String\& | The name to look up. |

### ReturnValue

The atomized string or **nullptr** if the string has not already been atomized.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
