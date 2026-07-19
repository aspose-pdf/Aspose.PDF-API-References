---
title: "Метод System::Xml::XPath::XPathNavigator::MoveTo"
linktitle: "MoveTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::MoveTo. При переопределении в производном классе перемещает XPathNavigator в то же положение, что и указанный XPathNavigator в C++."
type: docs
weight: 5000
url: /ru/cpp/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo method


При переопределении в производном классе перемещает [XPathNavigator](../) в то же положение, что и указанный [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| other | SharedPtr\<XPathNavigator\> | [XPathNavigator](../), расположенный на узле, к которому вы хотите переместиться. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the same position as the specified [XPathNavigator](../); otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
