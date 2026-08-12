---
title: "Метод System::Xml::XPath::XPathNavigator::LookupNamespace"
linktitle: "LookupNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::LookupNamespace. Возвращает URI пространства имён для указанного префикса в C++."
type: docs
weight: 4700
url: /ru/cpp/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace method


Возвращает URI пространства имён для указанного префикса.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const String\& | Префикс, URI пространства имён которого вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте [String::Empty](../../../system/string/empty/). |

### ReturnValue

Строка [String](../../../system/string/), содержащая URI пространства имён, назначенный указанному префиксу; **nullptr**, если для указанного префикса не назначен URI пространства имён. Возвращённая [String](../../../system/string/) атомизирована.

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
