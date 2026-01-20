---
title: System::Xml::XmlTextWriter::WriteSurrogateCharEntity method
linktitle: WriteSurrogateCharEntity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextWriter::WriteSurrogateCharEntity method. Generates and writes the surrogate character entity for the surrogate character pair in C++.'
type: docs
weight: 4000
url: /cpp/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity method


Generates and writes the surrogate character entity for the surrogate character pair.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | The low surrogate. This must be a value between **0xDC00** and **0xDFFF**. |
| highChar | char16_t | The high surrogate. This must be a value between **0xD800** and **0xDBFF**. |

## See Also

* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
