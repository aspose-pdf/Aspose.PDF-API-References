---
title: "System::Xml::Schema::XmlSchemaCollection::Add método"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Schema::XmlSchemaCollection::Add. Añade el XmlSchema a la colección en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method


Añade el [XmlSchema](../../xmlschema/) a la colección.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | El [XmlSchema](../../xmlschema/) para añadir a la colección. |

### ReturnValue

El objeto [XmlSchema](../../xmlschema/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Añade el [XmlSchema](../../xmlschema/) a la colección. El [XmlResolver](../../../system.xml/xmlresolver/) especificado se utiliza para resolver cualquier referencia externa.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | El [XmlSchema](../../xmlschema/) para añadir a la colección. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver los espacios de nombres referenciados en los elementos **include** y **import**. Si es **nullptr**, las referencias externas no se resuelven. |

### ReturnValue

El [XmlSchema](../../xmlschema/) añadido a la colección de esquemas.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method


Agrega todos los espacios de nombres definidos en la colección dada (incluyendo sus esquemas asociados) a esta colección.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchemaCollection\>\& | La [XmlSchemaCollection](../) que deseas añadir a esta colección. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaCollection](../)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method


Añade el esquema contenido en el [XmlReader](../../../system.xml/xmlreader/) a la colección de esquemas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const String\& | El URI del espacio de nombres asociado al esquema. Para los esquemas XML, típicamente será el **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) que contiene el esquema a añadir. |

### ReturnValue

El [XmlSchema](../../xmlschema/) añadido a la colección de esquemas; **nullptr** si el esquema que se está añadiendo es un esquema XDR o si hay errores de compilación en el esquema.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Añade el esquema contenido en el [XmlReader](../../../system.xml/xmlreader/) a la colección de esquemas. El [XmlResolver](../../../system.xml/xmlresolver/) especificado se utiliza para resolver cualquier recurso externo.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const String\& | El URI del espacio de nombres asociado al esquema. Para los esquemas XML, típicamente será el **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) que contiene el esquema a añadir. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver los espacios de nombres referenciados en los elementos **include** y **import** o el atributo **x-schema** (esquemas XDR). Si es **nullptr**, las referencias externas no se resuelven. |

### ReturnValue

El [XmlSchema](../../xmlschema/) añadido a la colección de esquemas; **nullptr** si el esquema que se está añadiendo es un esquema XDR o si hay errores de compilación en el esquema.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const String\&) method


Agrega el esquema ubicado por la URL proporcionada a la colección de esquemas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const String\& | El URI del espacio de nombres asociado al esquema. Para los esquemas XML, típicamente será el **targetNamespace**. |
| uri | const String\& | La URL que especifica el esquema a cargar. |

### ReturnValue

El [XmlSchema](../../xmlschema/) añadido a la colección de esquemas; **nullptr** si el esquema que se está añadiendo es un esquema XDR o si hay errores de compilación en el esquema.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
