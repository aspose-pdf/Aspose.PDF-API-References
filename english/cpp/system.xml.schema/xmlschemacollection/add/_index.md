---
title: System::Xml::Schema::XmlSchemaCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaCollection::Add method. Adds the XmlSchema to the collection in C++.'
type: docs
weight: 200
url: /cpp/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method


Adds the [XmlSchema](../../xmlschema/) to the collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | The [XmlSchema](../../xmlschema/) to add to the collection. |

### ReturnValue

The [XmlSchema](../../xmlschema/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Adds the [XmlSchema](../../xmlschema/) to the collection. The specified [XmlResolver](../../../system.xml/xmlresolver/) is used to resolve any external references.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | The [XmlSchema](../../xmlschema/) to add to the collection. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve namespaces referenced in **include** and **import** elements. If this is **nullptr**, external references are not resolved. |

### ReturnValue

The [XmlSchema](../../xmlschema/) added to the schema collection.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method


Adds all the namespaces defined in the given collection (including their associated schemas) to this collection.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchemaCollection\>\& | The [XmlSchemaCollection](../) you want to add to this collection. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaCollection](../)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method


Adds the schema contained in the [XmlReader](../../../system.xml/xmlreader/) to the schema collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | const String\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) containing the schema to add. |

### ReturnValue

The [XmlSchema](../../xmlschema/) added to the schema collection; **nullptr** if the schema being added is an XDR schema or if there are compilation errors in the schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Adds the schema contained in the [XmlReader](../../../system.xml/xmlreader/) to the schema collection. The specified [XmlResolver](../../../system.xml/xmlresolver/) is used to resolve any external resources.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | const String\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the **targetNamespace**. |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) containing the schema to add. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve namespaces referenced in **include** and **import** elements or **x-schema** attribute (XDR schemas). If this is **nullptr**, external references are not resolved. |

### ReturnValue

The [XmlSchema](../../xmlschema/) added to the schema collection; **nullptr** if the schema being added is an XDR schema or if there are compilation errors in the schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Add(const String\&, const String\&) method


Adds the schema located by the given URL into the schema collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | const String\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the **targetNamespace**. |
| uri | const String\& | The URL that specifies the schema to load. |

### ReturnValue

The [XmlSchema](../../xmlschema/) added to the schema collection; **nullptr** if the schema being added is an XDR schema or if there are compilation errors in the schema.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
