---
title: "Метод System::Xml::Xsl::IXsltContextFunction::Invoke"
linktitle: "Invoke"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Xsl::IXsltContextFunction::Invoke. Предоставляет способ вызова функции с заданными аргументами в указанном контексте в C++."
type: docs
weight: 500
url: /ru/cpp/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke method


Предоставляет метод для вызова функции с заданными аргументами в указанном контексте.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xsltContext | SharedPtr\<XsltContext\> | Контекст XSLT для вызова функции. |
| args | ArrayPtr\<SharedPtr\<Object\>\> | Аргументы вызова функции. Каждый аргумент является элементом массива. |
| docContext | SharedPtr\<System::Xml::XPath::XPathNavigator\> | Контекстный узел для вызова функции. |

### ReturnValue

[Object](../../../system/object/) представляет возвращаемое значение функции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
