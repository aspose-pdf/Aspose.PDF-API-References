---
title: "System::Xml::XPath::XPathExpression::SetContext metod"
linktitle: "SetContext"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathExpression::SetContext metod. När den åsidosätts i en avledd klass specificerar den IXmlNamespaceResolver‑objektet som ska användas för namnrymdsuppslag i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) method


När den åsidosätts i en avledd klass specificerar den [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som ska användas för namnrymdsuppslag.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Ett objekt som implementerar [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-gränssnittet för att användas vid namnrymdsuppslag. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) method


När den åsidosätts i en avledd klass specificerar den [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)-objektet som ska användas för namnrymdsuppslag.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nsManager | SharedPtr\<XmlNamespaceManager\> | Ett [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)-objekt att använda för namnrymdsuppslag. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
