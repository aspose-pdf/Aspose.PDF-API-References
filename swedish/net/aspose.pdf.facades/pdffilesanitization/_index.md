---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSanitization klass. Representerar sanering och återställnings-API. Använd den om du inte kan skapa/öppna dokument på något annat sätt
type: docs
weight: 4540
url: /sv/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization klass

Representerar sanering och återställnings-API. Använd den om du inte kan skapa/öppna dokument på något annat sätt.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentet som fasaden arbetar med. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Efter att filen har sparats kan du kontrollera vad som gjordes med filen. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Möjliggör att generera ny xref och trailer för dokumentet. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Möjliggör att ta bort data efter pdf-data. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Möjliggör att ta bort data före pdf-data. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Binder en Pdf-ström för sanering. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Binder en Pdf-fil för sanering. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Stänger fasaden. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter fasaden. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Tar bort gammal xref med trailer och skapar en ny xref med trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Återställer dokumentet. Använd egenskaper för att anpassa. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Sparar resultat-PDF till ström. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Sparar resultat-PDF till fil. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Tar bort data efter sista %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Tar bort data före %PDF. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)