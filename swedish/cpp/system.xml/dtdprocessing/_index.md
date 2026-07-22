---
title: "System::Xml::DtdProcessing enum"
linktitle: "DtdProcessing"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::DtdProcessing enum. Specificerar alternativen för bearbetning av DTD:er. DtdProcessing‑enumerationen används av XmlReaderSettings-klassen i C++."
type: docs
weight: 4700
url: /sv/cpp/system.xml/dtdprocessing/
---
## DtdProcessing enum


Specificerar alternativen för bearbetning av DTD:er. Enumerationen [DtdProcessing](./) används av klassen [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Prohibit | 0 | Specificerar att när en DTD påträffas, kastas ett [XmlException](../xmlexception/) med ett meddelande som anger att DTD:er är förbjudna. Detta är standardbeteendet. |
| Ignorera | 1 | Gör så att DOCTYPE-elementet ignoreras. Ingen DTD-behandling sker, och DTD/DOCTYPE går förlorad i utdata. |
| Analysera | 2 | Används för att analysera DTD:er. |

## Se även

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
