---
title: System::Xml::XmlNodeReader::ReadString method
linktitle: ReadString
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::ReadString method. Reads the contents of an element or text node as a string in C++.'
type: docs
weight: 3600
url: /cpp/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString method


Reads the contents of an element or text node as a string.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### ReturnValue

The contents of the element or text-like node (This can include CDATA, [Text](../../../system.text/) nodes, and so on). This can be an empty string if the reader is positioned on something other than an element or text node, or if there is no more text content to return in the current context. Note: The text node can be either an element or an attribute text node.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
