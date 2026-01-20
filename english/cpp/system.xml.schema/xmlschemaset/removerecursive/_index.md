---
title: System::Xml::Schema::XmlSchemaSet::RemoveRecursive method
linktitle: RemoveRecursive
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSet::RemoveRecursive method. Removes the specified XML Schema definition language (XSD) schema and all the schemas it imports from the XmlSchemaSet in C++.'
type: docs
weight: 1400
url: /cpp/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive method


Removes the specified XML [Schema](../../) definition language (XSD) schema and all the schemas it imports from the [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schemaToRemove | const SharedPtr\<XmlSchema\>\& | The [XmlSchema](../../xmlschema/) object to remove from the [XmlSchemaSet](../). |

### ReturnValue

**true** if the [XmlSchema](../../xmlschema/) object and all its imports were successfully removed; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
