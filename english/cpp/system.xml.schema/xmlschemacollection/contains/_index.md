---
title: System::Xml::Schema::XmlSchemaCollection::Contains method
linktitle: Contains
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaCollection::Contains method. Returns a value indicating whether the targetNamespace of the specified XmlSchema is in the collection in C++.'
type: docs
weight: 300
url: /cpp/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Returns a value indicating whether the **targetNamespace** of the specified [XmlSchema](../../xmlschema/) is in the collection.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | The [XmlSchema](../../xmlschema/) object. |

### ReturnValue

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Contains(const String\&) method


Returns a value indicating whether a schema with the specified namespace is in the collection.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | const String\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the target namespace. |

### ReturnValue

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
