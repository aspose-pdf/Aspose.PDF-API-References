---
title: System::Xml::XmlWriter::WriteNode method
linktitle: WriteNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::WriteNode method. When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling in C++.'
type: docs
weight: 2600
url: /cpp/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method


When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | The [XmlReader](../../xmlreader/) to read from. |
| defattr | bool | **true** to copy the default attributes from the [XmlReader](../../xmlreader/); otherwise, **false**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method


Copies everything from the XPathNavigator object to the writer. The position of the XPathNavigator remains unchanged.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| navigator | SharedPtr\<XPath::XPathNavigator\> | The XPathNavigator to copy from. |
| defattr | bool | **true** to copy the default attributes; otherwise, **false**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
