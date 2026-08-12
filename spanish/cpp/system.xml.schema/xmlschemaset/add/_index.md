---
title: "System::Xml::Schema::XmlSchemaSet::Add método"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSet::Add método. Añade el XmlSchema proporcionado al XmlSchemaSet en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Añade el [XmlSchema](../../xmlschema/) proporcionado al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | El objeto [XmlSchema](../../xmlschema/) a añadir al [XmlSchemaSet](../). |

### ReturnValue

Un objeto [XmlSchema](../../xmlschema/) si el esquema es válido. Si el esquema no es válido y se especifica un [ValidationEventHandler](../../validationeventhandler/), entonces se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una [XmlSchemaException](../../xmlschemaexception/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Añade todos los esquemas del lenguaje de definición de XML [Schema](../../) (XSD) del [XmlSchemaSet](../) proporcionado al [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | El objeto [XmlSchemaSet](../). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Añade el esquema del lenguaje de definición de XML [Schema](../../) (XSD) contenido en el [XmlReader](../../../system.xml/xmlreader/) al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | String | El valor **targetNamespace** del esquema, o **nullptr** para usar el **targetNamespace** especificado en el esquema. |
| schemaDocument | const SharedPtr\<XmlReader\>\& | El objeto [XmlReader](../../../system.xml/xmlreader/). |

### ReturnValue

Un objeto [XmlSchema](../../xmlschema/) si el esquema es válido. Si el esquema no es válido y se especifica un [ValidationEventHandler](../../validationeventhandler/), entonces se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una [XmlSchemaException](../../xmlschemaexception/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const String\&) method


Agrega el esquema del lenguaje de definición XML [Schema](../../) (XSD) en la URL especificada al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | String | El valor **targetNamespace** del esquema, o **nullptr** para usar el **targetNamespace** especificado en el esquema. |
| schemaUri | const String\& | La URL que especifica el esquema a cargar. |

### ReturnValue

Un objeto [XmlSchema](../../xmlschema/) si el esquema es válido. Si el esquema no es válido y se especifica un [ValidationEventHandler](../../validationeventhandler/), entonces se devuelve **nullptr** y se genera el evento de validación correspondiente. De lo contrario, se lanza una [XmlSchemaException](../../xmlschemaexception/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
