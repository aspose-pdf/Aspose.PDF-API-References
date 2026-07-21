---
title: "System::Xml::Schema::XmlSchemaInference::InferSchema método"
linktitle: "InferSchema"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaInference::InferSchema método. Infiere un esquema de Lenguaje de Definición de Esquema XML (XSD) a partir del documento XML contenido en el objeto XmlReader especificado en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


Infiere un [Schema](../../) de Lenguaje de Definición (XSD) a partir del documento XML contenido en el objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene el documento XML del cual inferir un esquema. |

### ReturnValue

Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene los esquemas inferidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


Infierne un esquema XML [Schema](../../) Definition Language (XSD) a partir del documento XML contenido en el objeto [XmlReader](../../../system.xml/xmlreader/) especificado, y refina el esquema inferido usando un esquema existente en el objeto [XmlSchemaSet](../../xmlschemaset/) especificado con el mismo espacio de nombres de destino.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene el documento XML del cual inferir un esquema. |
| schemas | SharedPtr\<XmlSchemaSet\> | Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene un esquema existente usado para refinar el esquema inferido. |

### ReturnValue

Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene los esquemas inferidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
