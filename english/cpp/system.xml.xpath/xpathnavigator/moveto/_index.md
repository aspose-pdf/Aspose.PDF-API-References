---
title: System::Xml::XPath::XPathNavigator::MoveTo method
linktitle: MoveTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::MoveTo method. When overridden in a derived class, moves the XPathNavigator to the same position as the specified XPathNavigator in C++.'
type: docs
weight: 5000
url: /cpp/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo method


When overridden in a derived class, moves the [XPathNavigator](../) to the same position as the specified [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | SharedPtr\<XPathNavigator\> | The [XPathNavigator](../) positioned on the node that you want to move to. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the same position as the specified [XPathNavigator](../); otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
