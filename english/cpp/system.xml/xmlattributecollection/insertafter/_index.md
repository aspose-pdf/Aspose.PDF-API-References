---
title: System::Xml::XmlAttributeCollection::InsertAfter method
linktitle: InsertAfter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttributeCollection::InsertAfter method. Inserts the specified attribute immediately after the specified reference attribute in C++.'
type: docs
weight: 400
url: /cpp/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter method


Inserts the specified attribute immediately after the specified reference attribute.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newNode | const SharedPtr\<XmlAttribute\>\& | The attribute to insert. |
| refNode | const SharedPtr\<XmlAttribute\>\& | The reference attribute. **newNode** is placed after the **refNode**. |

### ReturnValue

The [XmlAttribute](../../xmlattribute/) to insert into the collection.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
