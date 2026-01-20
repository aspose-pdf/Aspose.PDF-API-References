---
title: System::Xml::XmlAttribute::InsertBefore method
linktitle: InsertBefore
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttribute::InsertBefore method. Inserts the specified node immediately before the specified reference node in C++.'
type: docs
weight: 1500
url: /cpp/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore method


Inserts the specified node immediately before the specified reference node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | The [XmlNode](../../xmlnode/) to insert. |
| refChild | SharedPtr\<XmlNode\> | The [XmlNode](../../xmlnode/) that is the reference node. The **newChild** is placed before this node. |

### ReturnValue

The [XmlNode](../../xmlnode/) inserted.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
