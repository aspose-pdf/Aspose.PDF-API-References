---
title: System::Xml::XPath::XPathNavigator::InsertAfter method
linktitle: InsertAfter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::InsertAfter method. Returns an XmlWriter object used to create a new sibling node after the currently selected node in C++.'
type: docs
weight: 4100
url: /cpp/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() method


Returns an [XmlWriter](../../../system.xml/xmlwriter/) object used to create a new sibling node after the currently selected node.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### ReturnValue

An [XmlWriter](../../../system.xml/xmlwriter/) object used to create a new sibling node after the currently selected node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) method


Creates a new sibling node after the currently selected node using the XML contents of the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | SharedPtr\<XmlReader\> | An [XmlReader](../../../system.xml/xmlreader/) object positioned on the XML data for the new sibling node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) method


Creates a new sibling node after the currently selected node using the nodes in the [XPathNavigator](../) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | SharedPtr\<XPathNavigator\> | An [XPathNavigator](../) object positioned on the node to add as the new sibling node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::InsertAfter(String) method


Creates a new sibling node after the currently selected node using the XML string specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | String | The XML data string for the new sibling node. |

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
