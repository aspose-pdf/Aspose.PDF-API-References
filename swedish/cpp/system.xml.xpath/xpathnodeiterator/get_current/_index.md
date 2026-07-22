---
title: "System::Xml::XPath::XPathNodeIterator::get_Current‑metod"
linktitle: "get_Current"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNodeIterator::get_Current‑metod. När den åsidosätts i en avledd klass hämtar den XPathNavigator‑objektet för detta XPathNodeIterator, placerat på den aktuella kontextnoden i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current method


När den åsidosätts i en avledd klass hämtar den [XPathNavigator](../../xpathnavigator/)‑objektet för detta [XPathNodeIterator](../), placerat på den aktuella kontextnoden.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### ReturnValue

Ett [XPathNavigator](../../xpathnavigator/)‑objekt placerat på kontextnoden från vilken nodmängden valdes. Metoden [XPathNodeIterator::MoveNext](../movenext/) måste anropas för att flytta [XPathNodeIterator](../) till den första noden i den valda mängden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../xpathnavigator/)
* Class [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
