---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en enum för nivån på täckning som tillhandahålls av digitala signaturer i ett dokument."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Representerar en enum för nivån på täckning som tillhandahålls av digitala signaturer i ett dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Indikerar att dokumentet är helt täckt av digitala signaturer. Detta värde betyder att alla nödvändiga delar av dokumentet har signerats och att inga signaturer är komprometterade. |
| [PartiallySigned](#PartiallySigned) | Indikerar att dokumentet är delvis signerat, vilket betyder att en del, men inte hela, av dess innehåll är täckt av digitala signaturer. Detta värde används när vissa delar av dokumentet förblir osignerade eller är undantagna från signaturtäckningen. |
| [Undefined](#Undefined) | Indikerar att tillståndet för digitala signaturers täckning i dokumentet är odefinierat. Detta värde används vanligtvis när en eller flera signaturer i dokumentet är komprometterade eller inte kan verifieras, vilket förhindrar en definitiv bedömning av dokumentets signaturtäckning. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Indikerar att dokumentet är helt täckt av digitala signaturer. Detta värde betyder att alla nödvändiga delar av dokumentet har signerats och att inga signaturer är komprometterade.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Indikerar att dokumentet är delvis signerat, vilket betyder att en del, men inte hela, av dess innehåll är täckt av digitala signaturer. Detta värde används när vissa delar av dokumentet förblir osignerade eller är undantagna från signaturtäckningen.

### Undefined {#Undefined}
```
public static final int Undefined
```

Indikerar att tillståndet för digitala signaturers täckning i dokumentet är odefinierat. Detta värde används vanligtvis när en eller flera signaturer i dokumentet är komprometterade eller inte kan verifieras, vilket förhindrar en definitiv bedömning av dokumentets signaturtäckning.
