---
title: "System::Xml::XmlReader::ReadElementContentAs metod"
linktitle: "ReadElementContentAs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadElementContentAs metod. Läser elementets innehåll som den begärda typen i C++."
type: docs
weight: 5200
url: /sv/cpp/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Läser elementets innehåll som den begärda typen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const TypeInfo\& | Typen på värdet som ska returneras. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Ett [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)‑objekt som används för att lösa eventuella namnrymdsprefix relaterade till typkonvertering. |

### ReturnValue

Elementets innehåll konverterat till det begärda typade objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) method


Kontrollerar att det angivna lokala namnet och namnrymds‑URI matchar det för det aktuella elementet, och läser sedan elementets innehåll som den begärda typen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const TypeInfo\& | Typen på värdet som ska returneras. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Ett [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)‑objekt som används för att lösa eventuella namnrymdsprefix relaterade till typkonvertering. |
| localName | String | Det lokala namnet på elementet. |
| namespaceURI | String | Namnrymdens URI för elementet. |

### ReturnValue

Elementets innehåll konverterat till det begärda typade objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
