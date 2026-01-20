---
title: System::Xml::XPath::XPathNavigator::SelectChildren method
linktitle: SelectChildren
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::SelectChildren method. Selects all the child nodes of the current node that have the local name and namespace URI specified in C++.'
type: docs
weight: 7300
url: /cpp/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(String, String) method


Selects all the child nodes of the current node that have the local name and namespace URI specified.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the child nodes. |
| namespaceURI | String | The namespace URI of the child nodes. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectChildren(XPathNodeType) method


Selects all the child nodes of the current node that have the matching [XPathNodeType](../../xpathnodetype/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XPathNodeType | The [XPathNodeType](../../xpathnodetype/) of the child nodes. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
