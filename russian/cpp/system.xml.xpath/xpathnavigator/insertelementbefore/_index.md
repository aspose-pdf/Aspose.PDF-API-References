---
title: "System::Xml::XPath::XPathNavigator::InsertElementBefore метод"
linktitle: "InsertElementBefore"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::InsertElementBefore метод. Создает новый соседний элемент перед текущим узлом, используя указанные префикс пространства имен, локальное имя и URI пространства имен, с указанным значением в C++."
type: docs
weight: 4400
url: /ru/cpp/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore method


Создает новый соседний элемент перед текущим узлом, используя указанный префикс пространства имен, локальное имя и URI пространства имен, а также указанное значение.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | String | Префикс пространства имен нового дочернего элемента (если есть). |
| localName | String | Локальное имя нового дочернего элемента (если есть). |
| namespaceURI | String | URI пространства имен нового дочернего элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| value | String | Значение нового дочернего элемента. Если переданы [String::Empty](../../../system/string/empty/) или **nullptr**, создается пустой элемент. |

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
