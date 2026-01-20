---
title: System::Xml::XmlTextReader::get_LocalName method
linktitle: get_LocalName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::get_LocalName method. Returns the local name of the current node in C++.'
type: docs
weight: 1800
url: /cpp/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName method


Returns the local name of the current node.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### ReturnValue

The name of the current node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**. For node types that do not have a name (like **[Text](../../../system.text/)**, **Comment**, and so on), this method returns [String::Empty](../../../system/string/empty/).

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
