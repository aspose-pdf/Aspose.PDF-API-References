---
title: "Aspose::Pdf::Facades::KeySize enum"
linktitle: "KeySize"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::KeySize enum. Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument i C++."
type: docs
weight: 4800
url: /sv/cpp/aspose.pdf.facades/keysize/
---
## KeySize enum


Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument.

```cpp
enum class KeySize
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| x40 | 0 | 40-bit nyckel. Sådan nyckelstorlek används med RC4-algoritmen och ger låg säkerhetsnivå. Ändå kan äldre versioner av pdf-dokument endast krypteras med sådana nycklar (v. 1.3 och lägre); |
| x128 | 1 | 128-bit nyckel. Både RC4- och AES-algoritmer kan använda en sådan nyckelstorlek. |
| x256 | 2 | 256-bit nyckel. En sådan nyckelstorlek kan endast användas med AES och känns igen av de senaste Adobe Reader-versionerna (från och med v.9). |

## Se även

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
