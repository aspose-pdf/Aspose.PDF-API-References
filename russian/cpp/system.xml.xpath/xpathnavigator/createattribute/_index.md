---
title: "System::Xml::XPath::XPathNavigator::CreateAttribute метод"
linktitle: "CreateAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::CreateAttribute метод. Создаёт узел атрибута в текущем элементе, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением, указанным в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute method


Создаёт узел атрибута в текущем элементе, используя указанные префикс пространства имён, локальное имя и URI пространства имён, а также указанное значение.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | String | Префикс пространства имён нового узла атрибута (если есть). |
| localName | String | Локальное имя нового узла атрибута, которое не может быть [String::Empty](../../../system/string/empty/) или **nullptr**. |
| namespaceURI | String | URI пространства имён для нового узла атрибута (если есть). |
| value | String | Значение нового узла атрибута. Если переданы [String::Empty](../../../system/string/empty/) или **nullptr**, создаётся пустой узел атрибута. |

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
