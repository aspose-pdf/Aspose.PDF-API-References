---
title: "Метод System::Xml::XPath::XPathNavigator::ValueAs"
linktitle: "ValueAs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::ValueAs. Возвращает значение текущего узла как указанный тип, используя указанный объект IXmlNamespaceResolver для разрешения префиксов пространств имён в C++."
type: docs
weight: 8100
url: /ru/cpp/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs method


Возвращает значение текущего узла как указанный тип, используя объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const TypeInfo\& | Тип, в котором возвращается значение текущего узла. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### ReturnValue

Значение текущего узла в запрошенном типе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
