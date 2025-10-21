---
title: System::Xml::Schema::XmlSchemaSet::Reprocess method
linktitle: Reprocess
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSet::Reprocess method. Reprocesses an XML Schema definition language (XSD) schema that already exists in the XmlSchemaSet in C++.'
type: docs
weight: 1500
url: /cpp/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess method


Reprocesses an XML [Schema](../../) definition language (XSD) schema that already exists in the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schema | SharedPtr\<XmlSchema\> | The schema to reprocess. |

### ReturnValue

An [XmlSchema](../../xmlschema/) object if the schema is a valid schema. If the schema is not valid and a [ValidationEventHandler](../../validationeventhandler/) is specified, **nullptr** is returned and the appropriate validation event is raised. Otherwise, an [XmlSchemaException](../../xmlschemaexception/) is thrown.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
