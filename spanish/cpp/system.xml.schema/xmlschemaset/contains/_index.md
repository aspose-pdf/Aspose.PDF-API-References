---
title: "System::Xml::Schema::XmlSchemaSet::Contains método"
linktitle: "Contiene"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSet::Contains método. Indica si el objeto XmlSchema de lenguaje de definición de esquema XML (XSD) especificado está en el XmlSchemaSet en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) method


Indica si el objeto [XmlSchema](../../xmlschema/) de lenguaje de definición de [Schema](../../) XML (XSD) especificado está en el [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | El objeto [XmlSchema](../../xmlschema/). |

### ReturnValue

**true** if the [XmlSchema](../../xmlschema/) object is in the [XmlSchemaSet](../); otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Contains(String) method


Indica si un [Schema](../../) XML de lenguaje de definición (XSD) con el URI del espacio de nombres de destino especificado está en el [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | String | La propiedad **targetNamespace** del esquema. |

### ReturnValue

**true** if a schema with the specified target namespace URI is in the [XmlSchemaSet](../); otherwise, **false**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
