---
title: "Delegat SignHash"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Delegat för anpassad signering av dokumenthashen"
type: docs
weight: 5380
url: /sv/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Delegat för att anpassat signera dokumentets hash.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | Byte[] | Inmatningshash för dokumentet. |
| digestHashAlgorithm | DigestHashAlgorithm | Digest-algoritmen som används för att skapa hashvärdet. Värdet kommer aldrig att vara lika med Auto. |

### Returvärde

Utsignatur.

## Anmärkningar

Observera att oavsett om den digitala signaturen är fristående eller inte, kommer hash‑argumentet alltid att vara den slutgiltiga hash som ska signeras.

### Se även

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


