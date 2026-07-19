---
title: "Метод System::Xml::XPath::XPathNavigator::Select"
linktitle: "Select"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::Select. Выбирает набор узлов, используя указанный XPathExpression, в C++."
type: docs
weight: 7100
url: /ru/cpp/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(SharedPtr\<XPathExpression\>) method


Выбирает набор узлов, используя указанный [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Объект [XPathExpression](../../xpathexpression/), содержащий скомпилированный запрос [XPath](../../). |

### ReturnValue

[XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String) method


Выбирает набор узлов, используя указанное выражение [XPath](../../).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | String | [String](../../../system/string/), представляющий выражение [XPath](../../). |

### ReturnValue

[XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) method


Выбирает набор узлов, используя указанное выражение [XPath](../../) и объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | String | [String](../../../system/string/), представляющий выражение [XPath](../../). |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### ReturnValue

[XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
