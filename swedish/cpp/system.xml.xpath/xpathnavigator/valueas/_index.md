---
title: "System::Xml::XPath::XPathNavigator::ValueAs‑metod"
linktitle: "ValueAs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::ValueAs‑metod. Returnerar den aktuella nodens värde som den angivna typen, med hjälp av det angivna IXmlNamespaceResolver‑objektet för att lösa namnrymdspräfix i C++."
type: docs
weight: 8100
url: /sv/cpp/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs method


Returnerar den aktuella nodens värde som den angivna typen, med hjälp av det angivna [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)‑objektet för att lösa namnrymdspräfix.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const TypeInfo\& | Den typ som nodens värde ska returneras som. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)‑objekt som används för att lösa namnrymdsprefix. |

### ReturnValue

Värdet för den aktuella noden som den begärda typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
