---
title: "Метод System::Xml::XPath::XPathNodeIterator::get_Current"
linktitle: "get_Current"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNodeIterator::get_Current. При переопределении в производном классе получает объект XPathNavigator для этого XPathNodeIterator, расположенный на текущем контекстном узле в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current method


При переопределении в производном классе получает объект [XPathNavigator](../../xpathnavigator/) для этого [XPathNodeIterator](../), расположенный на текущем контекстном узле.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### ReturnValue

Объект [XPathNavigator](../../xpathnavigator/), расположенный на контекстном узле, из которого был выбран набор узлов. Метод [XPathNodeIterator::MoveNext](../movenext/) должен быть вызван, чтобы переместить [XPathNodeIterator](../) к первому узлу в выбранном наборе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../xpathnavigator/)
* Class [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
