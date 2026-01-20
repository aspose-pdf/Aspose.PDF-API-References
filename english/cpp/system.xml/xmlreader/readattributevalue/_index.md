---
title: System::Xml::XmlReader::ReadAttributeValue method
linktitle: ReadAttributeValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadAttributeValue method. When overridden in a derived class, parses the attribute value into one or more Text, EntityReference, or EndEntity nodes in C++.'
type: docs
weight: 3800
url: /cpp/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue method


When overridden in a derived class, parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## See Also

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
