---
title: "System::Xml::Schema::XmlSchemaSet::Schemas method"
linktitle: "Esquemas"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSet::Schemas method. Devuelve una colección de todos los esquemas del lenguaje de definición de XML Schema (XSD) en el XmlSchemaSet en C++."
type: docs
weight: 1600
url: /es/cpp/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


Devuelve una colección de todos los esquemas del lenguaje de definición de XML [Schema](../../) (XSD) en el [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### ReturnValue

Un objeto IList que contiene todos los esquemas que se han añadido al [XmlSchemaSet](../). Si no se han añadido esquemas al [XmlSchemaSet](../), se devuelve una colección vacía.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Schemas(String) method


Devuelve una colección de todos los esquemas del lenguaje de definición de XML [Schema](../../) (XSD) en el [XmlSchemaSet](../) que pertenecen al espacio de nombres especificado.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | String | La propiedad **targetNamespace** del esquema. |

### ReturnValue

Un objeto IList que contiene todos los esquemas que se han añadido al [XmlSchemaSet](../) que pertenecen al espacio de nombres especificado. Si no se han añadido esquemas al [XmlSchemaSet](../), se devuelve una colección vacía.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
