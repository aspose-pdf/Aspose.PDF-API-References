---
title: "System::Xml::IXmlNamespaceResolver-klass"
linktitle: "IXmlNamespaceResolver"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::IXmlNamespaceResolver-klass. Tillhandahåller skrivskyddad åtkomst till en uppsättning prefix‑ och namnrymdsmappningar i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml/ixmlnamespaceresolver/
---
## IXmlNamespaceResolver class


Tillhandahåller skrivskyddad åtkomst till en uppsättning prefix- och namnrymdsmappningar.

```cpp
class IXmlNamespaceResolver : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) | Returnerar en samling av definierade prefix-namnområdesmappningar som för närvarande är i omfång. |
| virtual [LookupNamespace](./lookupnamespace/)(const String\&) | Returnerar namnrymdens URI som är mappad till det angivna prefixet. |
| virtual [LookupPrefix](./lookupprefix/)(const String\&) | Returnerar prefixet som är mappat till den angivna namnrymdens URI. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
