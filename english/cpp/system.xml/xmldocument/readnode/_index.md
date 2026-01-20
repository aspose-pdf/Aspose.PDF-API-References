---
title: System::Xml::XmlDocument::ReadNode method
linktitle: ReadNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument::ReadNode method. Creates an XmlNode object based on the information in the XmlReader. The reader must be positioned on a node or attribute in C++.'
type: docs
weight: 3600
url: /cpp/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode method


Creates an [XmlNode](../../xmlnode/) object based on the information in the [XmlReader](../../xmlreader/). The reader must be positioned on a node or attribute.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | The XML source. |

### ReturnValue

The new [XmlNode](../../xmlnode/) or **nullptr** if no more nodes exist.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
