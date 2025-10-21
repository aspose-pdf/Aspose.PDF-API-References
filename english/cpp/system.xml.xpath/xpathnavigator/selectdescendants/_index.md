---
title: System::Xml::XPath::XPathNavigator::SelectDescendants method
linktitle: SelectDescendants
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::SelectDescendants method. Selects all the descendant nodes of the current node with the local name and namespace URI specified in C++.'
type: docs
weight: 7400
url: /cpp/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(String, String, bool) method


Selects all the descendant nodes of the current node with the local name and namespace URI specified.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the descendant nodes. |
| namespaceURI | String | The namespace URI of the descendant nodes. |
| matchSelf | bool | **true** to include the context node in the selection; otherwise, **false**. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectDescendants(XPathNodeType, bool) method


Selects all the descendant nodes of the current node that have a matching [XPathNodeType](../../xpathnodetype/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XPathNodeType | The [XPathNodeType](../../xpathnodetype/) of the descendant nodes. |
| matchSelf | bool | **true** to include the context node in the selection; otherwise, **false**. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
