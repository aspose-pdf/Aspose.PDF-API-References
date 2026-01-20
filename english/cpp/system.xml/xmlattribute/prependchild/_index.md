---
title: System::Xml::XmlAttribute::PrependChild method
linktitle: PrependChild
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttribute::PrependChild method. Adds the specified node to the beginning of the list of child nodes for this node in C++.'
type: docs
weight: 1600
url: /cpp/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild method


Adds the specified node to the beginning of the list of child nodes for this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | The [XmlNode](../../xmlnode/) to add. If it is an [XmlDocumentFragment](../../xmldocumentfragment/), the entire contents of the document fragment are moved into the child list of this node. |

### ReturnValue

The [XmlNode](../../xmlnode/) added.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
