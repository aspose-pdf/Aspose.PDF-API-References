---
title: System::Xml::XPath::XPathNodeIterator::get_Current method
linktitle: get_Current
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNodeIterator::get_Current method. When overridden in a derived class, gets the XPathNavigator object for this XPathNodeIterator, positioned on the current context node in C++.'
type: docs
weight: 400
url: /cpp/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current method


When overridden in a derived class, gets the [XPathNavigator](../../xpathnavigator/) object for this [XPathNodeIterator](../), positioned on the current context node.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### ReturnValue

An [XPathNavigator](../../xpathnavigator/) object positioned on the context node from which the node set was selected. The [XPathNodeIterator::MoveNext](../movenext/) method must be called to move the [XPathNodeIterator](../) to the first node in the selected set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../xpathnavigator/)
* Class [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
