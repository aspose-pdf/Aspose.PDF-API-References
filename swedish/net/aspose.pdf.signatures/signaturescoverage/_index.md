---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage enum. Representerar enum för nivån av täckning som tillhandahålls av digitala signaturer i ett dokument
type: docs
weight: 10110
url: /sv/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

Representerar enum för nivån av täckning som tillhandahålls av digitala signaturer i ett dokument.

```csharp
public enum SignaturesCoverage
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Undefined | `0` | Indikerar att tillståndet för digitala signaturers täckning i dokumentet är odefinierat. Detta värde används vanligtvis när en eller flera signaturer i dokumentet är komprometterade eller inte kan verifieras, vilket förhindrar en definitiv bedömning av dokumentets signaturtäckning. |
| EntirelySigned | `1` | Indikerar att dokumentet är helt täckt av digitala signaturer. Detta värde betyder att alla nödvändiga delar av dokumentet har signerats och inga signaturer är komprometterade. |
| PartiallySigned | `2` | Indikerar att dokumentet är delvis signerat, vilket innebär att vissa, men inte alla, av dess innehåll är täckt av digitala signaturer. Detta värde används när vissa delar av dokumentet förblir osignerade eller utesluts från signaturtäckningen. |

### Se Även

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)