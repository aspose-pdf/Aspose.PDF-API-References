---
title: "Метод System::Xml::XPath::XPathExpression::Compile"
linktitle: "Compile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathExpression::Compile. Компилирует указанное XPath‑выражение и возвращает объект XPathExpression, представляющий XPath‑выражение в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method


Компилирует указанное выражение [XPath](../../) и возвращает объект [XPathExpression](../), представляющий выражение [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const String\& | Выражение [XPath](../../). |

### ReturnValue

Объект [XPathExpression](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method


Компилирует указанное выражение [XPath](../../) с использованием объекта [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), указанного для разрешения пространств имён, и возвращает объект [XPathExpression](../), представляющий выражение [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const String\& | Выражение [XPath](../../). |
| nsResolver | const SharedPtr\<IXmlNamespaceResolver\>\& | Объект, реализующий интерфейс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения пространств имён. |

### ReturnValue

Объект [XPathExpression](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
