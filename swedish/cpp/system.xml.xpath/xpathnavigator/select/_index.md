---
title: "System::Xml::XPath::XPathNavigator::Select metod"
linktitle: "Välj"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::Select metod. Väljer en noduppsättning med den angivna XPathExpression i C++."
type: docs
weight: 7100
url: /sv/cpp/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(SharedPtr\<XPathExpression\>) method


Väljer en noduppsättning med den angivna [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Ett [XPathExpression](../../xpathexpression/) objekt som innehåller den kompilerade [XPath](../../)-frågan. |

### ReturnValue

En [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String) method


Väljer en noduppsättning, med det angivna [XPath](../../)-uttrycket.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | String | En [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |

### ReturnValue

En [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) method


Väljer en noduppsättning med det angivna [XPath](../../)-uttrycket med det angivna [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | String | En [String](../../../system/string/) som representerar ett [XPath](../../)-uttryck. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)‑objekt som används för att lösa namnrymdsprefix. |

### ReturnValue

En [XPathNodeIterator](../../xpathnodeiterator/) som pekar på den valda noduppsättningen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
