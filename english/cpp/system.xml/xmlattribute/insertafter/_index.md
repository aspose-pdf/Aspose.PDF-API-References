---
title: System::Xml::XmlAttribute::InsertAfter method
linktitle: InsertAfter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttribute::InsertAfter method. Inserts the specified node immediately after the specified reference node in C++.'
type: docs
weight: 1400
url: /cpp/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter method


Inserts the specified node immediately after the specified reference node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | The [XmlNode](../../xmlnode/) to insert. |
| refChild | SharedPtr\<XmlNode\> | The [XmlNode](../../xmlnode/) that is the reference node. The **newChild** is placed after the **refChild**. |

### ReturnValue

The [XmlNode](../../xmlnode/) inserted.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
