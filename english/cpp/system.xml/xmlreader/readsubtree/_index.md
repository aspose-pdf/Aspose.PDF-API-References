---
title: System::Xml::XmlReader::ReadSubtree method
linktitle: ReadSubtree
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadSubtree method. Returns a new XmlReader instance that can be used to read the current node, and all its descendants in C++.'
type: docs
weight: 7000
url: /cpp/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree method


Returns a new [XmlReader](../) instance that can be used to read the current node, and all its descendants.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### ReturnValue

A new XML reader instance set to [ReadState::Initial](../../readstate/). Calling the [XmlReader::Read](../read/) method positions the new reader on the node that was current before the call to the [XmlReader::ReadSubtree](./) method.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
