---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att kontrollera dokumentets digitala signaturer för kompromettering."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Representerar en klass för att kontrollera dokumentets digitala signaturer för kompromettering.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Hämtar en samling av digitala signaturer som har identifierats som komprometterade. Denna egenskap innehåller listan över alla komprometterade signaturer som upptäckts i dokumentet. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Hämtar täckningsstatusen för digitala signaturer i ett dokument. Om den är lika med {@code SignaturesCoverage#Undefined} är en av signaturerna komprometterad. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Indikerar om det finns några komprometterade digitala signaturer i dokumentet. Returnerar true om minst en signatur är komprometterad; annars false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Hämtar en samling av digitala signaturer som har identifierats som komprometterade. Denna egenskap innehåller listan över alla komprometterade signaturer som upptäckts i dokumentet.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Hämtar täckningsstatusen för digitala signaturer i ett dokument. Om den är lika med {@code SignaturesCoverage#Undefined} är en av signaturerna komprometterad.

**Returns:**
SignaturesCoverage‑element

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Indikerar om det finns några komprometterade digitala signaturer i dokumentet. Returnerar true om minst en signatur är komprometterad; annars false.

**Returns:**
booleskt värde
