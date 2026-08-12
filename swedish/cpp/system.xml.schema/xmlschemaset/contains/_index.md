---
title: "System::Xml::Schema::XmlSchemaSet::Contains metod"
linktitle: "Innehåller"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSet::Contains metod. Anger om det angivna XML Schema definition language (XSD) XmlSchema-objektet finns i XmlSchemaSet i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) method


Anger om det angivna XML [Schema](../../) definition language (XSD) [XmlSchema](../../xmlschema/) objektet finns i [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | [XmlSchema](../../xmlschema/) objektet. |

### ReturnValue

**true** if the [XmlSchema](../../xmlschema/) object is in the [XmlSchemaSet](../); otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Contains(String) method


Anger om ett XML [Schema](../../) definition language (XSD) schema med den angivna mål‑namnrymdens URI finns i [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | String | Schemat **targetNamespace**‑egenskap. |

### ReturnValue

**true** if a schema with the specified target namespace URI is in the [XmlSchemaSet](../); otherwise, **false**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
