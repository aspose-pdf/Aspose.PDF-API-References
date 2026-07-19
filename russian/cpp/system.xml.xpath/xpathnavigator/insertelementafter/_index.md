---
title: "Метод System::Xml::XPath::XPathNavigator::InsertElementAfter"
linktitle: "InsertElementAfter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::InsertElementAfter. Создаёт новый соседний элемент после текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён, со значением, указанным в C++."
type: docs
weight: 4300
url: /ru/cpp/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter method


Создает новый соседний элемент после текущего узла, используя указанный префикс пространства имен, локальное имя и URI пространства имен, а также указанное значение.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
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
