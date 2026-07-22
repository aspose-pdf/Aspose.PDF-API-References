---
title: "System::Xml::XmlTextWriter::WriteSurrogateCharEntity metod"
linktitle: "WriteSurrogateCharEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextWriter::WriteSurrogateCharEntity metod. Genererar och skriver surrogat-teckenenheten för surrogat-teckenparet i C++."
type: docs
weight: 4000
url: /sv/cpp/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity method


Genererar och skriver surrogate-teckenentiteten för surrogate-teckenparet.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowChar | char16_t | Den låga surrogaten. Detta måste vara ett värde mellan **0xDC00** och **0xDFFF**. |
| highChar | char16_t | Den höga surrogaten. Detta måste vara ett värde mellan **0xD800** och **0xDBFF**. |

## Se även

* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
