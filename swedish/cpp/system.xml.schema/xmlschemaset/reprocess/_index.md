---
title: "System::Xml::Schema::XmlSchemaSet::Reprocess‑metod"
linktitle: "Omprocessa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSet::Reprocess metod. Omprocessar ett XML Schema definition language (XSD) schema som redan finns i XmlSchemaSet i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess method


Omprocessar ett XML [Schema](../../) definition language (XSD) schema som redan finns i [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | SharedPtr\<XmlSchema\> | Schemat att omprocessa. |

### ReturnValue

Ett [XmlSchema](../../xmlschema/) objekt om schemat är ett giltigt schema. Om schemat inte är giltigt och en [ValidationEventHandler](../../validationeventhandler/) anges, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett [XmlSchemaException](../../xmlschemaexception/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
