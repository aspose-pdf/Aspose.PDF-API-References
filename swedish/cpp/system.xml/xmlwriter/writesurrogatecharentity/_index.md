---
title: "System::Xml::XmlWriter::WriteSurrogateCharEntity metod"
linktitle: "WriteSurrogateCharEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter::WriteSurrogateCharEntity metod. När den åsidosätts i en avledd klass, genererar och skriver surrogate‑tecken‑enheten för surrogate‑tecken‑paret i C++."
type: docs
weight: 3400
url: /sv/cpp/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity method


När den åsidosätts i en avledd klass genererar och skriver den surrogate-teckenentiteten för surrogate-teckenparet.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowChar | char16_t | Den låga surrogate. Detta måste vara ett värde mellan 0xDC00 och 0xDFFF. |
| highChar | char16_t | Den höga surrogate. Detta måste vara ett värde mellan 0xD800 och 0xDBFF. |

## Se även

* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
