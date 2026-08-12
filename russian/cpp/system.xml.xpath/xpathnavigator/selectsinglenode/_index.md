---
title: "Метод System::Xml::XPath::XPathNavigator::SelectSingleNode"
linktitle: "SelectSingleNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::SelectSingleNode. Выбирает один узел в XPathNavigator, используя указанный объект XPathExpression в C++."
type: docs
weight: 7500
url: /ru/cpp/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method


Выбирает один узел в [XPathNavigator](../), используя указанный объект [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | SharedPtr\<XPathExpression\> | Объект [XPathExpression](../../xpathexpression/), содержащий скомпилированный запрос [XPath](../../). |

### ReturnValue

Объект [XPathNavigator](../), содержащий первый подходящий узел для указанного запроса [XPath](../../); в противном случае **nullptr**, если результаты запроса отсутствуют.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String) method


Выбирает один узел в [XPathNavigator](../), используя указанный запрос [XPath](../../).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | String | [String](../../../system/string/), представляющий выражение [XPath](../../). |

### ReturnValue

Объект [XPathNavigator](../), содержащий первый подходящий узел для указанного запроса [XPath](../../); в противном случае **nullptr**, если результаты запроса отсутствуют.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method


Выбирает один узел в объекте [XPathNavigator](../), используя указанный запрос [XPath](../../) и указанный объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | String | [String](../../../system/string/), представляющий выражение [XPath](../../). |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён в запросе [XPath](../../). |

### ReturnValue

Объект [XPathNavigator](../), содержащий первый подходящий узел для указанного запроса [XPath](../../); в противном случае **nullptr**, если результаты запроса отсутствуют.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
