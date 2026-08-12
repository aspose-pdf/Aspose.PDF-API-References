---
title: "Метод System::Xml::XPath::XPathItem::ValueAs"
linktitle: "ValueAs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathItem::ValueAs. Возвращает значение элемента как указанный тип в C++."
type: docs
weight: 1100
url: /ru/cpp/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) method


Возвращает значение элемента в указанном типе.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const TypeInfo\& | Тип, в который следует вернуть значение элемента. |

### ReturnValue

Значение элемента в запрошенном типе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


При переопределении в производном классе возвращает значение элемента в типе, указанном с использованием объекта [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), предназначенного для разрешения префиксов пространств имён.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const TypeInfo\& | Тип, в котором следует вернуть значение элемента. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### ReturnValue

Значение элемента в запрошенном типе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
