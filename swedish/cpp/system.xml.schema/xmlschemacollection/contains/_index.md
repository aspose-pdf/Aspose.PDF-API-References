---
title: "System::Xml::Schema::XmlSchemaCollection::Contains metod"
linktitle: "Innehåller"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaCollection::Contains metod. Returnerar ett värde som indikerar om targetNamespace för den angivna XmlSchema finns i samlingen i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Returnerar ett värde som indikerar om **targetNamespace** för den angivna [XmlSchema](../../xmlschema/) finns i samlingen.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | [XmlSchema](../../xmlschema/) objektet. |

### ReturnValue

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Contains(const String\&) method


Returnerar ett värde som indikerar om ett schema med den angivna namnrymden finns i samlingen.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const String\& | Namnrums-URI:n som är associerad med schemat. För XML-scheman kommer detta vanligtvis att vara målnamnrymden. |

### ReturnValue

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
