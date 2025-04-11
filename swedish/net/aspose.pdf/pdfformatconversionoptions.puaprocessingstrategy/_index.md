---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy enum. Vissa PDF-dokument har speciella unicode-symboler som tillhör Private Use Area (PUA), se beskrivning på https//en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler orsakar PDF/A-kompatibla fel som "Text är mappad till Unicode Private Use Area men ingen ActualText-post finns". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA-symboler.
type: docs
weight: 8390
url: /sv/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy uppräkning

Vissa PDF-dokument har speciella unicode-symboler som tillhör Private Use Area (PUA), se beskrivning på https://en.wikipedia.org/wiki/Private_Use_Areas. Dessa symboler orsakar PDF/A-kompatibla fel som "Text är mappad till Unicode Private Use Area men ingen ActualText-post finns". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA-symboler.

```csharp
public enum PuaProcessingStrategy
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Inaktivera PUA-symbolbehandling. Denna strategi används som standard för PDF/A-dokument med nivå B-överensstämmelse. |
| SurroundPuaTextWithEmptyActualText | `1` | Infogar markerat innehållsblock med ActualText-post som innehåller tom text. Denna strategi ger bra resultat för dokument utan markerade innehållsblock. Används som standard för PDF/A-dokument med nivå A-överensstämmelse. |
| SubstitutePuaSymbols | `2` | Denna strategi fungerar långsammare än 'SurroundPuaTextWithEmptyActualText' men den kan ta bort PUA-kompatibla fel för dokument som inte kan hanteras korrekt av SurroundPuaTextWithEmptyActualText. PUA-symboler ersätts med symbolen 'space' eller specialunicode (vissa PUA-symboler har unicode-analoger). Ersättning tillämpas inte på dokumentets text utan på teckensnittets interna data ToUnicode, så det påverkar inte symbolens visning men det påverkar symbolens presentation i kopiera/klistra in operationens systembuffer. |

### Se Även

* klass [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)