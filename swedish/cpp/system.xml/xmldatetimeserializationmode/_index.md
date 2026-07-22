---
title: "System::Xml::XmlDateTimeSerializationMode enum"
linktitle: "XmlDateTimeSerializationMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDateTimeSerializationMode enum. Anger hur tidsvärdet ska behandlas vid konvertering mellan sträng och DateTime i C++."
type: docs
weight: 5800
url: /sv/cpp/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Anger hur tidsvärdet ska behandlas vid konvertering mellan sträng och [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Local | 0 | Behandla som lokal tid. Om [DateTime](../../system/datetime/)‑objektet representerar Coordinated Universal Time (UTC) konverteras det till lokal tid. |
| Utc | 1 | Behandla som UTC. Om [DateTime](../../system/datetime/)‑objektet representerar lokal tid konverteras det till UTC. |
| Unspecified | 2 | Behandla som lokal tid om en [DateTime](../../system/datetime/) konverteras till en sträng. Om en sträng konverteras till [DateTime](../../system/datetime/), konvertera till lokal tid om en tidszon är specificerad. |
| RoundtripKind | 3 | Tidszonsinformation bör bevaras vid konvertering. |

## Se även

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
