---
title: "Enum SignaturesCoverage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Signatures.SignaturesCoverage enum. Representerar enum för nivån av täckning som tillhandahålls av digitala signaturer i ett Document."
type: docs
weight: 10290
url: /sv/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

Representerar en enum för täckningsnivån som tillhandahålls av digitala signaturer i ett dokument.

```csharp
public enum SignaturesCoverage
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Undefined | `0` | Indikerar att tillståndet för digitala signaturers täckning i Document är odefinierat. Detta värde används vanligtvis när en eller flera signaturer i Document är komprometterade eller inte kan verifieras, vilket förhindrar en definitiv bedömning av Document's signaturtäckning. |
| EntirelySigned | `1` | Indikerar att Document är helt täckt av digitala signaturer. Detta värde betyder att alla nödvändiga delar av Document har signerats och att inga signaturer är komprometterade. |
| PartiallySigned | `2` | Indikerar att Document är delvis signerat, vilket betyder att vissa, men inte alla, delar av dess innehåll är täckta av digitala signaturer. Detta värde används när vissa delar av Document förblir osignerade eller exkluderas från signaturtäckningen. |

### Se även

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


