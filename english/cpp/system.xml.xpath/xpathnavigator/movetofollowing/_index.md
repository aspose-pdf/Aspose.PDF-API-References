---
title: System::Xml::XPath::XPathNavigator::MoveToFollowing method
linktitle: MoveToFollowing
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::MoveToFollowing method. Moves the XPathNavigator to the element with the local name and namespace URI specified in document order in C++.'
type: docs
weight: 5700
url: /cpp/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) method


Moves the [XPathNavigator](../) to the element with the local name and namespace URI specified in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the element. |
| namespaceURI | String | The namespace URI of the element. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) method


Moves the [XPathNavigator](../) to the element with the local name and namespace URI specified, to the boundary specified, in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the element. |
| namespaceURI | String | The namespace URI of the element. |
| end | SharedPtr\<XPathNavigator\> | The [XPathNavigator](../) object positioned on the element boundary which the current [XPathNavigator](../) will not move past while searching for the following element. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType) method


Moves the [XPathNavigator](../) to the following element of the [XPathNodeType](../../xpathnodetype/) specified in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XPathNodeType | The [XPathNodeType](../../xpathnodetype/) of the element. The [XPathNodeType](../../xpathnodetype/) cannot be [XPathNodeType::Attribute](../../xpathnodetype/) or [XPathNodeType::Namespace](../../xpathnodetype/). |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) method


Moves the [XPathNavigator](../) to the following element of the [XPathNodeType](../../xpathnodetype/) specified, to the boundary specified, in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XPathNodeType | The [XPathNodeType](../../xpathnodetype/) of the element. The [XPathNodeType](../../xpathnodetype/) cannot be [XPathNodeType::Attribute](../../xpathnodetype/) or [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | SharedPtr\<XPathNavigator\> | The [XPathNavigator](../) object positioned on the element boundary which the current [XPathNavigator](../) will not move past while searching for the following element. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
