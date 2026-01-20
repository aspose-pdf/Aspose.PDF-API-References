---
title: System::Xml::XPath::XPathNavigator::MoveToAttribute method
linktitle: MoveToAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::MoveToAttribute method. Moves the XPathNavigator to the attribute with the matching local name and namespace URI in C++.'
type: docs
weight: 5100
url: /cpp/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute method


Moves the [XPathNavigator](../) to the attribute with the matching local name and namespace URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute; **nullptr** for an empty namespace. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the attribute; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
