---
title: System::Xml::XPath::XPathNavigator::CreateAttribute method
linktitle: CreateAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::CreateAttribute method. Creates an attribute node on the current element node using the namespace prefix, local name and namespace URI specified with the value specified in C++.'
type: docs
weight: 700
url: /cpp/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute method


Creates an attribute node on the current element node using the namespace prefix, local name and namespace URI specified with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The namespace prefix of the new attribute node (if any). |
| localName | String | The local name of the new attribute node which cannot [String::Empty](../../../system/string/empty/) or **nullptr**. |
| namespaceURI | String | The namespace URI for the new attribute node (if any). |
| value | String | The value of the new attribute node. If [String::Empty](../../../system/string/empty/) or **nullptr** are passed, an empty attribute node is created. |

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
