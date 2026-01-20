---
title: System::Xml::XmlAttribute::get_BaseURI method
linktitle: get_BaseURI
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttribute::get_BaseURI method. Returns the base Uniform Resource Identifier (URI) of the node in C++.'
type: docs
weight: 300
url: /cpp/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI method


Returns the base Uniform Resource Identifier (URI) of the node.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### ReturnValue

The location from which the node was loaded or [String::Empty](../../../system/string/empty/) if the node has no base URI. [Attribute](../../../system/attribute/) nodes have the same base URI as their owner element. If an attribute node does not have an owner element, get_BaseURI returns [String::Empty](../../../system/string/empty/).

## See Also

* Class [String](../../../system/string/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
