---
title: "System::Xml::XPath::XPathItem::ValueAs metod"
linktitle: "ValueAs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathItem::ValueAs metod. Returnerar objektets värde som den angivna typen i C++."
type: docs
weight: 1100
url: /sv/cpp/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) method


Returnerar objektets värde som den angivna typen.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const TypeInfo\& | Typen att returnera objektets värde som. |

### ReturnValue

Värdet på objektet som den begärda typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


När den åsidosätts i en avledd klass, returnerar den objektets värde som den typ som anges med hjälp av [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)‑objektet som specificeras för att lösa namnrymdsprefix.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const TypeInfo\& | Typen att returnera objektets värde som. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)‑objekt som används för att lösa namnrymdsprefix. |

### ReturnValue

Värdet på objektet som den begärda typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
