---
title: System::Xml::Schema::XmlSchemaObjectCollection::Contains method
linktitle: Contains
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaObjectCollection::Contains method. Indicates if the specified XmlSchemaObject is in the XmlSchemaObjectCollection in C++.'
type: docs
weight: 300
url: /cpp/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains method


Indicates if the specified [XmlSchemaObject](../../xmlschemaobject/) is in the [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const SharedPtr\<XmlSchemaObject\>\& | The [XmlSchemaObject](../../xmlschemaobject/). |

### ReturnValue

**true** if the specified qualified name is in the collection; otherwise, returns **false**. If **nullptr** is supplied, **false** is returned because there is no qualified name with a null name.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
