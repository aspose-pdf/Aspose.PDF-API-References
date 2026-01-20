---
title: System::Xml::XmlWriter::WriteRaw method
linktitle: WriteRaw
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::WriteRaw method. When overridden in a derived class, writes raw markup manually from a character buffer in C++.'
type: docs
weight: 2900
url: /cpp/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method


When overridden in a derived class, writes raw markup manually from a character buffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArrayPtr\<char16_t\> | Character array containing the text to write. |
| index | int32_t | The position within the buffer indicating the start of the text to write. |
| count | int32_t | The number of characters to write. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteRaw(const String\&) method


When overridden in a derived class, writes raw markup manually from a string.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const String\& | [String](../../../system/string/) containing the text to write. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
