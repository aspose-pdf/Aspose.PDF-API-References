---
title: "Enum PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy enum. Vissa PDF‑dokument har speciella Unicode‑symboler som tillhör Private Use Area PUA, se beskrivning på https//en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler orsakar PDF/A‑kompatibla fel som exempelvis \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA‑symboler"
type: docs
weight: 8530
url: /sv/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Vissa PDF‑dokument har speciella Unicode‑symboler som tillhör Private Use Area (PUA), se beskrivning på https://en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler orsakar PDF/A‑kompatibla fel som exempelvis "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA‑symboler.

```csharp
public enum PuaProcessingStrategy
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Inaktivera PUA‑symbolbehandling. Denna strategi används som standard för PDF/A‑dokument med nivå B‑överensstämmelse. |
| SurroundPuaTextWithEmptyActualText | `1` | Infogar markerat innehållsblock med ActualText‑post som innehåller tom text. Denna strategi ger bra resultat för dokument utan markerade innehållsblock. Används som standard för PDF/A‑dokument med nivå A‑överensstämmelse. |
| SubstitutePuaSymbols | `2` | Denna strategi fungerar långsammare än 'SurroundPuaTextWithEmptyActualText' men den kan ta bort PUA‑kompatibla fel för dokument som inte kan hanteras korrekt av SurroundPuaTextWithEmptyActualText. PUA‑symboler ersätts med tecknet 'space' eller speciell Unicode (vissa PUA‑symboler har Unicode‑analoger). Ersättningen tillämpas inte på dokumentets text utan på fontens interna ToUnicode‑data, så den påverkar inte symbolens visuella framställning men den påverkar symbolens presentation i kopiera/klistra‑in‑operationens systembuffert. |

### Se även

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


