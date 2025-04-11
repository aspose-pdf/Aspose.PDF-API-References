---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delegate för att anpassa signaturen av dokumenthashen
type: docs
weight: 5260
url: /sv/net/aspose.pdf.forms/signhash/
---
## SignHash-delegat

Delegate för att anpassa signaturen av dokumenthashen.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | Byte[] | Indatahash för dokumentet. |
| digestHashAlgorithm | DigestHashAlgorithm | Den digest-algoritm som används för att skapa hashen. Värdet kommer aldrig att vara lika med Auto. |

### Returvärde

Utdata signatur.

## Anmärkningar

Observera att oavsett om den digitala signaturen är fristående eller inte, kommer hash-argumentet alltid att vara den slutliga hash som ska signeras.

### Se Även

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)