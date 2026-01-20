---
title: System::Xml::XPath::XPathNavigator::AppendChild method
linktitle: AppendChild
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::AppendChild method. Returns an XmlWriter object used to create one or more new child nodes at the end of the list of child nodes of the current node in C++.'
type: docs
weight: 100
url: /cpp/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() method


Returns an [XmlWriter](../../../system.xml/xmlwriter/) object used to create one or more new child nodes at the end of the list of child nodes of the current node.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### ReturnValue

An [XmlWriter](../../../system.xml/xmlwriter/) object used to create new child nodes at the end of the list of child nodes of the current node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) method


Creates a new child node at the end of the list of child nodes of the current node using the XML contents of the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newChild | SharedPtr\<XmlReader\> | An [XmlReader](../../../system.xml/xmlreader/) object positioned on the XML data for the new child node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) method


Creates a new child node at the end of the list of child nodes of the current node using the nodes in the [XPathNavigator](../) specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newChild | SharedPtr\<XPathNavigator\> | An [XPathNavigator](../) object positioned on the node to add as the new child node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(String) method


Creates a new child node at the end of the list of child nodes of the current node using the XML data string specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newChild | String | The XML data string for the new child node. |

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
