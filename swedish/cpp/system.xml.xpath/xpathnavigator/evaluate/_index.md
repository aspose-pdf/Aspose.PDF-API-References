---
title: "System::Xml::XPath::XPathNavigator::Evaluate metod"
linktitle: "Evaluate"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::Evaluate metod. Utvärderar XPathExpression och returnerar det typade resultatet i C++."
type: docs
weight: 1200
url: /sv/cpp/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) method


Utvärderar [XPathExpression](../../xpathexpression/) och returnerar det typade resultatet.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Ett [XPathExpression](../../xpathexpression/) som kan utvärderas. |

### ReturnValue

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller noduppsättning). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/) objekt respektive.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) method


Använder den medföljande kontexten för att utvärdera [XPathExpression](../../xpathexpression/), och returnerar det typade resultatet.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Ett [XPathExpression](../../xpathexpression/) som kan utvärderas. |
| context | SharedPtr\<XPathNodeIterator\> | En [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen som utvärderingen ska utföras på. |

### ReturnValue

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller noduppsättning). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/) objekt respektive.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(String) method


Utvärderar det angivna [XPath](../../)-uttrycket och returnerar det typade resultatet.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | String | En sträng som representerar ett [XPath](../../)-uttryck som kan utvärderas. |

### ReturnValue

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller noduppsättning). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/) objekt respektive.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) method


Utvärderar det angivna [XPath](../../)-uttrycket och returnerar det typade resultatet, med hjälp av det angivna [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix i [XPath](../../)-uttrycket.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | String | En sträng som representerar ett [XPath](../../)-uttryck som kan utvärderas. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som används för att lösa namnrymdsprefix i [XPath](../../)-uttrycket. |

### ReturnValue

Resultatet av uttrycket ([Boolean](../../../system/boolean/), nummer, sträng eller noduppsättning). Detta motsvarar [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) eller [XPathNodeIterator](../../xpathnodeiterator/) objekt respektive.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
