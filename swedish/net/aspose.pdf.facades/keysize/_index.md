---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.KeySize enum. Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument
type: docs
weight: 4390
url: /sv/net/aspose.pdf.facades/keysize/
---
## KeySize-uppräkning

Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument.

```csharp
public enum KeySize
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| x40 | `0` | 40 bitars nyckel. Sådan nyckelstorlek används med RC4-algoritmen och ger en låg säkerhetsnivå. Ändå kan gamla versioner av pdf-dokument endast krypteras med sådana nycklar (v. 1.3 och lägre); |
| x128 | `1` | 128 bitars nyckel. Både RC4- och AES-algoritmer kan använda sådan nyckelstorlek. |
| x256 | `2` | 256 bitars nyckel. Sådan nyckelstorlek kan endast användas med AES och erkänns av de senaste versionerna av Adobe Reader (från v.9). |

### Se Även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)