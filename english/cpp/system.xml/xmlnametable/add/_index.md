---
title: System::Xml::XmlNameTable::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNameTable::Add method. When overridden in a derived class, atomizes the specified string and adds it to the XmlNameTable in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


When overridden in a derived class, atomizes the specified string and adds it to the [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const ArrayPtr\<char16_t\>\& | The character array containing the name to add. |
| offset | int32_t | Zero-based index into the array specifying the first character of the name. |
| length | int32_t | The number of characters in the name. |

### ReturnValue

The new atomized string or the existing one if it already exists. If length is zero, [String::Empty](../../../system/string/empty/) is returned.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Add(const String\&) method


When overridden in a derived class, atomizes the specified string and adds it to the [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const String\& | The name to add. |

### ReturnValue

The new atomized string or the existing one if it already exists.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
