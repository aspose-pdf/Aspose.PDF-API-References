---
title: "System::Xml::Schema::XmlSchemaInference::InferSchema‑metod"
linktitle: "InferSchema"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaInference::InferSchema‑metod. Härleder ett XML Schema Definition Language (XSD)-schema från XML‑dokumentet som finns i det angivna XmlReader‑objektet i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


Härleder ett XML [Schema](../../) Definition Language (XSD)-schema från XML‑dokumentet som finns i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som innehåller XML‑dokumentet att härleda ett schema från. |

### ReturnValue

Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller de härledda schemana.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


Härleder ett XML [Schema](../../) Definition Language (XSD)-schema från XML‑dokumentet som finns i det angivna [XmlReader](../../../system.xml/xmlreader/)-objektet, och förfinar det härledda schemat med ett befintligt schema i det angivna [XmlSchemaSet](../../xmlschemaset/)-objektet med samma mål‑namnrymd.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som innehåller XML‑dokumentet att härleda ett schema från. |
| schemas | SharedPtr\<XmlSchemaSet\> | Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller ett befintligt schema som används för att förfina det härledda schemat. |

### ReturnValue

Ett [XmlSchemaSet](../../xmlschemaset/)-objekt som innehåller de härledda schemana.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
