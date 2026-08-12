---
title: "System::Xml::XmlDocument::CreateDocumentType metod"
linktitle: "CreateDocumentType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::CreateDocumentType metod. Returnerar ett nytt XmlDocumentType‑objekt i C++."
type: docs
weight: 700
url: /sv/cpp/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType method


Returnerar ett nytt [XmlDocumentType](../../xmldocumenttype/)‑objekt.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const String\& | Namnet på dokumenttypen. |
| publicId | const String\& | Den offentliga identifieraren för dokumenttypen eller **nullptr**. Du kan ange en offentlig URI och även en systemidentifierare för att identifiera platsen för den externa DTD‑delmängden. |
| systemId | const String\& | Systemidentifieraren för dokumenttypen eller **nullptr**. Anger URL:en till filens plats för den externa DTD‑delmängden. |
| internalSubset | const String\& | Den interna DTD‑delmängden för dokumenttypen eller **nullptr**. |

### ReturnValue

Den nya [XmlDocumentType](../../xmldocumenttype/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
