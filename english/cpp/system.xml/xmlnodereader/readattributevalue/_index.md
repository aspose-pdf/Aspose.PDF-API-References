---
title: System::Xml::XmlNodeReader::ReadAttributeValue method
linktitle: ReadAttributeValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::ReadAttributeValue method. Parses the attribute value into one or more Text, EntityReference, or EndEntity nodes in C++.'
type: docs
weight: 3100
url: /cpp/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue method


Parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## See Also

* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
