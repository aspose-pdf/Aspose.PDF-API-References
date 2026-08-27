---
title: "Enum KeySize"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.KeySize enum. Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument."
type: docs
weight: 4510
url: /sv/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

Definierar olika nyckelstorlekar som kan användas för att kryptera pdf Document.

```csharp
public enum KeySize
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| x40 | `0` | 40-bit nyckel. Sådan nyckelstorlek används med RC4-algoritmen och ger låg säkerhetsnivå. Trots detta kan äldre versioner av pdf-dokument endast krypteras med sådana nycklar (v. 1.3 och lägre); |
| x128 | `1` | 128-bit nyckel. Både RC4- och AES-algoritmer kan använda sådan nyckelstorlek. |
| x256 | `2` | 256-bit nyckel. Sådan nyckelstorlek kan endast användas med AES och känns igen av de senaste Adobe Reader-versionerna (från och med v.9). |

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


