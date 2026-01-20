---
title: System::Xml::Schema::XmlSchemaSet::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSet::Add method. Adds the given XmlSchema to the XmlSchemaSet in C++.'
type: docs
weight: 200
url: /cpp/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Adds the given [XmlSchema](../../xmlschema/) to the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | The [XmlSchema](../../xmlschema/) object to add to the [XmlSchemaSet](../). |

### ReturnValue

An [XmlSchema](../../xmlschema/) object if the schema is valid. If the schema is not valid and a [ValidationEventHandler](../../validationeventhandler/) is specified, then **nullptr** is returned and the appropriate validation event is raised. Otherwise, an [XmlSchemaException](../../xmlschemaexception/) is thrown.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Adds all the XML [Schema](../../) definition language (XSD) schemas in the given [XmlSchemaSet](../) to the [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | The [XmlSchemaSet](../) object. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Adds the XML [Schema](../../) definition language (XSD) schema contained in the [XmlReader](../../../system.xml/xmlreader/) to the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | String | The schema **targetNamespace** value, or **nullptr** to use the **targetNamespace** specified in the schema. |
| schemaDocument | const SharedPtr\<XmlReader\>\& | The [XmlReader](../../../system.xml/xmlreader/) object. |

### ReturnValue

An [XmlSchema](../../xmlschema/) object if the schema is valid. If the schema is not valid and a [ValidationEventHandler](../../validationeventhandler/) is specified, then **nullptr** is returned and the appropriate validation event is raised. Otherwise, an [XmlSchemaException](../../xmlschemaexception/) is thrown.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const String\&) method


Adds the XML [Schema](../../) definition language (XSD) schema at the URL specified to the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | String | The schema **targetNamespace** value, or **nullptr** to use the **targetNamespace** specified in the schema. |
| schemaUri | const String\& | The URL that specifies the schema to load. |

### ReturnValue

An [XmlSchema](../../xmlschema/) object if the schema is valid. If the schema is not valid and a [ValidationEventHandler](../../validationeventhandler/) is specified, then **nullptr** is returned and the appropriate validation event is raised. Otherwise, an [XmlSchemaException](../../xmlschemaexception/) is thrown.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
