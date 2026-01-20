---
title: System::Xml::XPath::XPathNavigator::GetAttribute method
linktitle: GetAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::GetAttribute method. Returns the value of the attribute with the specified local name and namespace URI in C++.'
type: docs
weight: 3800
url: /cpp/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute method


Returns the value of the attribute with the specified local name and namespace URI.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. **localName** is case-sensitive. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

A [String](../../../system/string/) that contains the value of the specified attribute; [String::Empty](../../../system/string/empty/) if a matching attribute is not found, or if the [XPathNavigator](../) is not positioned on an element node.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
