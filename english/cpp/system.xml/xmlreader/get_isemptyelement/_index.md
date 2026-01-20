---
title: System::Xml::XmlReader::get_IsEmptyElement method
linktitle: get_IsEmptyElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::get_IsEmptyElement method. When overridden in a derived class, gets a value indicating whether the current node is an empty element (for example, <MyElement/>) in C++.'
type: docs
weight: 1300
url: /cpp/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement method


When overridden in a derived class, gets a value indicating whether the current node is an empty element (for example, **<MyElement/>**).

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```


### ReturnValue

**true** if the current node is an element ([XmlReader::get_NodeType](../get_nodetype/) equals [XmlNodeType::Element](../../xmlnodetype/)) that ends with **/>**; otherwise, **false**.

## See Also

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
