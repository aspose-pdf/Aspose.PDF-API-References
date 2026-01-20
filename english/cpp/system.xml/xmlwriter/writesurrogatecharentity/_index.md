---
title: System::Xml::XmlWriter::WriteSurrogateCharEntity method
linktitle: WriteSurrogateCharEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::WriteSurrogateCharEntity method. When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair in C++.'
type: docs
weight: 3400
url: /cpp/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity method


When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | The low surrogate. This must be a value between 0xDC00 and 0xDFFF. |
| highChar | char16_t | The high surrogate. This must be a value between 0xD800 and 0xDBFF. |

## See Also

* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
