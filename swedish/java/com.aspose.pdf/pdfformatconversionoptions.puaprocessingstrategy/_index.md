---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Vissa PDF-dokument har speciella Unicode-symboler som tillhör Private Use Area (PUA), se beskrivning på https://en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler."
type: docs
weight: 3750
url: /sv/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Vissa PDF-dokument har speciella Unicode-symboler som tillhör Private Use Area (PUA), se beskrivningen på https://en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler orsakar PDF/A-kompatibla fel som "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA-symboler.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [None](#None) | Inaktivera PUA-symbolbearbetning. Denna strategi används som standard för PDF/A-dokument med nivå B-överensstämmelse. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Denna strategi fungerar långsammare än 'SurroundPuaTextWithEmptyActualText' men den kan ta bort PUA-kompatibla fel för dokument som inte kan hanteras korrekt av SurroundPuaTextWithEmptyActualText. PUA-symboler ersätts med symbolen 'space' eller speciell Unicode (vissa PUA-symboler har Unicode-analoger). Ersättningen tillämpas inte på dokumentets text utan på teckensnittets interna data ToUnicode, så den påverkar inte symbolens synlighet men den påverkar symbolens presentation i kopiera/klistra‑in‑operationens systembuffert. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Infogar ett markerat innehållsblock med ActualText‑post som innehåller tom text. Denna strategi ger bra resultat för dokument utan markerade innehållsblock. Används som standard för PDF/A-dokument med nivå A‑överensstämmelse. |

### None {#None}
```
public static final int None
```

Inaktivera PUA-symbolbearbetning. Denna strategi används som standard för PDF/A-dokument med nivå B-överensstämmelse.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Denna strategi fungerar långsammare än 'SurroundPuaTextWithEmptyActualText' men den kan ta bort PUA-kompatibla fel för dokument som inte kan hanteras korrekt av SurroundPuaTextWithEmptyActualText. PUA-symboler ersätts med symbolen 'space' eller speciell Unicode (vissa PUA-symboler har Unicode-analoger). Ersättningen tillämpas inte på dokumentets text utan på teckensnittets interna data ToUnicode, så den påverkar inte symbolens synlighet men den påverkar symbolens presentation i kopiera/klistra‑in‑operationens systembuffert.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Infogar ett markerat innehållsblock med ActualText‑post som innehåller tom text. Denna strategi ger bra resultat för dokument utan markerade innehållsblock. Används som standard för PDF/A-dokument med nivå A‑överensstämmelse.
