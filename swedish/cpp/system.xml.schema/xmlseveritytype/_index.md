---
title: "System::Xml::Schema::XmlSeverityType enum"
linktitle: "XmlSeverityType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSeverityType enum. Representerar allvaret i valideringshändelsen i C++."
type: docs
weight: 8100
url: /sv/cpp/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum


Representerar allvaret för valideringshändelsen.

```cpp
enum class XmlSeverityType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Error | 0 | Indikerar att ett valideringsfel inträffade när instansdokumentet validerades. Detta gäller dokumenttypdefinitioner (DTDs) och XML [Schema](../) definition language (XSD)-scheman. World Wide [Web](../../system.web/) Consortium (W3C)-validitetsregler betraktas som fel. Om ingen valideringshändelsehanterare har skapats, kastas ett undantag för fel. |
| Warning | 1 | Indikerar att en valideringshändelse inträffade som inte är ett fel. En varning utfärdas vanligtvis när det saknas DTD eller XML [Schema](../) att validera ett visst element eller attribut mot. Till skillnad från fel kastar varningar inte ett undantag om det inte finns någon valideringshändelsehanterare. |

## Se även

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
