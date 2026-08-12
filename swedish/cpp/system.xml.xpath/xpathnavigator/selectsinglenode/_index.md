---
title: "System::Xml::XPath::XPathNavigator::SelectSingleNode method"
linktitle: "SelectSingleNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::SelectSingleNode method. Väljer en enskild nod i XPathNavigator med hjälp av det angivna XPathExpression-objektet i C++."
type: docs
weight: 7500
url: /sv/cpp/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method


Väljer en enskild nod i [XPathNavigator](../) med det angivna [XPathExpression](../../xpathexpression/)-objektet.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | SharedPtr\<XPathExpression\> | Ett [XPathExpression](../../xpathexpression/) objekt som innehåller den kompilerade [XPath](../../)-frågan. |

### ReturnValue

Ett [XPathNavigator](../) objekt som innehåller den första matchande noden för den angivna [XPath](../../)-frågan; annars **nullptr** om det inte finns några resultat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String) method


Väljer en enskild nod i [XPathNavigator](../) med den angivna [XPath](../../)-frågan.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | String | En [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |

### ReturnValue

Ett [XPathNavigator](../) objekt som innehåller den första matchande noden för den angivna [XPath](../../)-frågan; annars, **nullptr** om det inte finns några resultat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method


Väljer en enskild nod i [XPathNavigator](../)-objektet med den angivna [XPath](../../)-frågan och det angivna [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | String | En [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som används för att lösa namnrymdsprefix i [XPath](../../)-frågan. |

### ReturnValue

Ett [XPathNavigator](../) objekt som innehåller den första matchande noden för den angivna [XPath](../../)-frågan; annars **nullptr** om det inte finns några resultat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
