---
title: "System::Xml::XPath::XPathNavigator::AppendChildElement метод"
linktitle: "AppendChildElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::AppendChildElement метод. Создает новый узел дочернего элемента в конце списка дочерних узлов текущего узла, используя указанный префикс пространства имен, локальное имя и URI пространства имен, заданные значением в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement method


Создаёт новый дочерний элементный узел в конце списка дочерних узлов текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён, а также указанное значение.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | String | Префикс пространства имен нового узла дочернего элемента (если есть). |
| localName | String | Локальное имя нового узла дочернего элемента (если есть). |
| namespaceURI | String | URI пространства имен нового узла дочернего элемента (если есть). [String::Empty](../../../system/string/empty/) и **nullptr** эквивалентны. |
| value | String | Значение нового узла дочернего элемента. Если переданы [String::Empty](../../../system/string/empty/) или **nullptr**, создается пустой элемент. |

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
