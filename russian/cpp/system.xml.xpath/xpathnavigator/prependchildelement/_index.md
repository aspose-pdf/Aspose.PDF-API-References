---
title: "System::Xml::XPath::XPathNavigator::PrependChildElement method"
linktitle: "PrependChildElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::PrependChildElement method. Создаёт новый дочерний элемент в начале списка дочерних узлов текущего узла, используя указанный префикс пространства имён, локальное имя и URI пространства имён, заданные значением в C++."
type: docs
weight: 6700
url: /ru/cpp/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement method


Создаёт новый дочерний элемент в начале списка дочерних узлов текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением, указанным.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
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
