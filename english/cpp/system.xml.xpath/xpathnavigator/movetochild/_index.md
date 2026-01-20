---
title: System::Xml::XPath::XPathNavigator::MoveToChild method
linktitle: MoveToChild
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::MoveToChild method. Moves the XPathNavigator to the child node with the local name and namespace URI specified in C++.'
type: docs
weight: 5200
url: /cpp/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) method


Moves the [XPathNavigator](../) to the child node with the local name and namespace URI specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the child node to move to. |
| namespaceURI | String | The namespace URI of the child node to move to. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToChild(XPathNodeType) method


Moves the [XPathNavigator](../) to the child node of the [XPathNodeType](../../xpathnodetype/) specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XPathNodeType | The [XPathNodeType](../../xpathnodetype/) of the child node to move to. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
