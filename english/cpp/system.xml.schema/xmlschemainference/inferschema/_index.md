---
title: System::Xml::Schema::XmlSchemaInference::InferSchema method
linktitle: InferSchema
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaInference::InferSchema method. Infers an XML Schema Definition Language (XSD) schema from the XML document contained in the XmlReader object specified in C++.'
type: docs
weight: 400
url: /cpp/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


Infers an XML [Schema](../../) Definition Language (XSD) schema from the XML document contained in the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) object containing the XML document to infer a schema from. |

### ReturnValue

An [XmlSchemaSet](../../xmlschemaset/) object containing the inferred schemas.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


Infers an XML [Schema](../../) Definition Language (XSD) schema from the XML document contained in the [XmlReader](../../../system.xml/xmlreader/) object specified, and refines the inferred schema using an existing schema in the [XmlSchemaSet](../../xmlschemaset/) object specified with the same target namespace.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | An [XmlReader](../../../system.xml/xmlreader/) object containing the XML document to infer a schema from. |
| schemas | SharedPtr\<XmlSchemaSet\> | An [XmlSchemaSet](../../xmlschemaset/) object containing an existing schema used to refine the inferred schema. |

### ReturnValue

An [XmlSchemaSet](../../xmlschemaset/) object containing the inferred schemas.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
