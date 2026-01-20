---
title: System::Xml::XmlReader::get_LocalName method
linktitle: get_LocalName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::get_LocalName method. When overridden in a derived class, gets the local name of the current node in C++.'
type: docs
weight: 1400
url: /cpp/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName method


When overridden in a derived class, gets the local name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### ReturnValue

The name of the current node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**. For node types that do not have a name (like **[Text](../../../system.text/)**, **Comment**, and so on), this method returns [String::Empty](../../../system/string/empty/).

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
