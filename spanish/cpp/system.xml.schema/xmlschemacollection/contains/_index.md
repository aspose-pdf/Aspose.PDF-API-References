---
title: "System::Xml::Schema::XmlSchemaCollection::Contains método"
linktitle: "Contiene"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaCollection::Contains método. Devuelve un valor que indica si el targetNamespace del XmlSchema especificado está en la colección en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Devuelve un valor que indica si el **targetNamespace** del [XmlSchema](../../xmlschema/) especificado está en la colección.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | El objeto [XmlSchema](../../xmlschema/). |

### ReturnValue

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Contains(const String\&) method


Devuelve un valor que indica si un esquema con el espacio de nombres especificado está en la colección.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const String\& | El URI de espacio de nombres asociado con el esquema. Para los esquemas XML, normalmente será el espacio de nombres objetivo. |

### ReturnValue

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
