---
title: System::Xml::XPath::XPathNodeIterator class
linktitle: XPathNodeIterator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNodeIterator class. Provides an iterator over a selected set of nodes in C++.'
type: docs
weight: 600
url: /cpp/system.xml.xpath/xpathnodeiterator/
---
## XPathNodeIterator class


Provides an iterator over a selected set of nodes.

```cpp
class XPathNodeIterator : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XPath::XPathNavigator>>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Clone](./clone/)() | When overridden in a derived class, returns a clone of this [XPathNodeIterator](./) object. |
| virtual [get_Count](./get_count/)() | Returns the index of the last node in the selected set of nodes. |
| virtual [get_Current](./get_current/)() | When overridden in a derived class, gets the [XPathNavigator](../xpathnavigator/) object for this [XPathNodeIterator](./), positioned on the current context node. |
| virtual [get_CurrentPosition](./get_currentposition/)() | When overridden in a derived class, gets the index of the current position in the selected set of nodes. |
| [GetEnumerator](./getenumerator/)() override | Returns an IEnumerator object to iterate through the selected node set. |
| virtual [MoveNext](./movenext/)() | When overridden in a derived class, moves the [XPathNavigator](../xpathnavigator/) object returned by the [XPathNodeIterator::get_Current](./get_current/) method to the next node in the selected node set. |
| [XPathNodeIterator](./xpathnodeiterator/)() | Initializes a new instance of the [XPathNodeIterator](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
