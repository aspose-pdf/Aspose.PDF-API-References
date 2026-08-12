---
title: "System::Xml::Schema::XmlSchemaValidationFlags-enum"
linktitle: "XmlSchemaValidationFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaValidationFlags-enum. Anger schemavalideringsalternativ som används av XmlSchemaValidator- och XmlReader-klasserna i C++."
type: docs
weight: 7900
url: /sv/cpp/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum


Anger schemavalideringsalternativ som används av klasserna [XmlSchemaValidator](../xmlschemavalidator/) och [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Bearbeta inte identitetsbegränsningar, inline‑scheman, schema‑plats‑tips eller rapportera varningar för schemavalidering. |
| ProcessInlineSchema | 1 | Bearbeta inline‑scheman som påträffas under validering. |
| ProcessSchemaLocation | 2 | Bearbeta schema‑plats‑tips (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) som påträffas under validering. |
| ReportValidationWarnings | 4 | Rapportera varningar för schemavalidering som påträffas under validering. |
| ProcessIdentityConstraints | 8 | Bearbeta identitetsbegränsningar (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) som påträffas under validering. |
| AllowXmlAttributes | 16 | Tillåt xml:*‑attribut även om de inte är definierade i schemat. Attributen kommer att valideras baserat på deras datatyp. |

## Se även

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
