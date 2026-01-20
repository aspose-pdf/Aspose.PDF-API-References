---
title: System::Xml::XPath::XPathNavigator::InsertElementBefore method
linktitle: InsertElementBefore
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::InsertElementBefore method. Creates a new sibling element before the current node using the namespace prefix, local name, and namespace URI specified, with the value specified in C++.'
type: docs
weight: 4400
url: /cpp/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore method


Creates a new sibling element before the current node using the namespace prefix, local name, and namespace URI specified, with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The namespace prefix of the new child element (if any). |
| localName | String | The local name of the new child element (if any). |
| namespaceURI | String | The namespace URI of the new child element (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. |
| value | String | The value of the new child element. If [String::Empty](../../../system/string/empty/) or **nullptr** are passed, an empty element is created. |

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
