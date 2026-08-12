---
title: "System::Xml::NewLineHandling enum"
linktitle: "NewLineHandling"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::NewLineHandling enum. Anger hur radbrytningar ska hanteras i C++."
type: docs
weight: 5200
url: /sv/cpp/system.xml/newlinehandling/
---
## NewLineHandling enum


Anger hur radbrytningar ska hanteras.

```cpp
enum class NewLineHandling
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Replace | 0 | Radbrytningstecken ersätts för att matcha tecknet som anges i värdet för [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Radbrytningstecken entitiseras. Denna inställning bevarar alla tecken när utdata läses av en normaliserande [XmlReader](../xmlreader/). |
| Ingen | 2 | Radbrytningstecknen förblir oförändrade. Utdata är samma som indata. |

## Se även

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
