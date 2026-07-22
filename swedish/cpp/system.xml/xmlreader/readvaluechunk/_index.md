---
title: "System::Xml::XmlReader::ReadValueChunk metod"
linktitle: "ReadValueChunk"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadValueChunk metod. Läser stora textströmmar som är inbäddade i ett XML-dokument i C++."
type: docs
weight: 7400
url: /sv/cpp/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk method


Läser stora textströmmar som är inbäddade i ett XML‑dokument.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | ArrayPtr\<char16_t\> | Den teckenarray som fungerar som bufferten dit textinnehållet skrivs. Detta värde kan inte vara **nullptr**. |
| index | int32_t | Offseten inom bufferten där [XmlReader](../) kan börja kopiera resultaten. |
| count | int32_t | Det maximala antalet tecken som ska kopieras till bufferten. Det faktiska antalet kopierade tecken returneras av denna metod. |

### ReturnValue

Antalet tecken som lästs in i bufferten. Värdet noll returneras när det inte finns mer textinnehåll.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
