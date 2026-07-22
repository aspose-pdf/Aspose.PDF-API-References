---
title: "Enum Aspose::Pdf::PdfFormatConversionOptions::PuaProcessingStrategy"
linktitle: "PuaProcessingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Enum Aspose::Pdf::PdfFormatConversionOptions::PuaProcessingStrategy. Vissa PDF-dokument har speciella Unicode-symboler som tillhör Private Use Area (PUA), se beskrivning på . Dessa symboler orsakar PDF/A‑kompatibla fel som \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA‑symboler i C++."
type: docs
weight: 4200
url: /sv/cpp/aspose.pdf/pdfformatconversionoptions/puaprocessingstrategy/
---
## PuaProcessingStrategy enum


Vissa PDF-dokument har speciella Unicode-symboler som tillhör Private Use Area (PUA), se beskrivningen på [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). Dessa symboler orsakar PDF/A-kompatibilitetsfel som "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA-symboler.

```cpp
enum class PuaProcessingStrategy
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Inaktivera bearbetning av PUA‑symboler. Denna strategi används som standard för PDF/A‑dokument med nivå B‑överensstämmelse. |
| SurroundPuaTextWithEmptyActualText | 1 | Infogar ett markerat innehållsblock med ActualText‑post som innehåller tom text. Denna strategi ger bra resultat för dokument utan markerade innehållsblock. Används som standard för PDF/A‑dokument med nivå A‑överensstämmelse. |
| SubstitutePuaSymbols | 2 | Denna strategi är långsammare än 'SurroundPuaTextWithEmptyActualText' men den kan ta bort PUA‑kompatibla fel för dokument som inte kan hanteras korrekt av SurroundPuaTextWithEmptyActualText. PUA‑symboler ersätts med symbolen 'space' eller special‑unicode (vissa PUA‑symboler har Unicode‑analoger). Ersättningen tillämpas inte på dokumentets text utan på fontens interna ToUnicode‑data, så den påverkar inte symbolens visuella utseende men den påverkar symbolens presentation i systemets kopiera/klistra‑in‑buffer. |

## Se även

* Class [PdfFormatConversionOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
