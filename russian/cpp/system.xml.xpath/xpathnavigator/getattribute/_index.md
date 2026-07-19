---
title: "Метод System::Xml::XPath::XPathNavigator::GetAttribute"
linktitle: "GetAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::GetAttribute. Возвращает значение атрибута с указанным локальным именем и URI пространства имён в C++."
type: docs
weight: 3800
url: /ru/cpp/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute method


Возвращает значение атрибута с указанным локальным именем и URI пространства имён.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. **localName** чувствительно к регистру. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Объект [String](../../../system/string/), содержащий значение указанного атрибута; [String::Empty](../../../system/string/empty/) если соответствующий атрибут не найден, либо если [XPathNavigator](../) не находится на узле‑элементе.

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
