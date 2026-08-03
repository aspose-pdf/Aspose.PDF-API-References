---
title: "Klass PdfFileSanitization"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileSanitization-klass. Representerar sanerings- och återställnings‑API. Använd den om du inte kan skapa/öppna dokument på annat sätt."
type: docs
weight: 4660
url: /sv/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

Representerar sanerings‑ och återställnings‑API. Använd den om du inte kan skapa/öppna dokument på annat sätt.

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Efter att filen har sparats kan du kontrollera vad som har gjorts med filen. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Tillåter att generera ny xref och trailer för dokumentet. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Tillåter att ta bort data efter pdf‑data |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Tillåter att ta bort data före pdf‑data. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Kopplar en Pdf‑ström för Sanitize. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Kopplar en Pdf‑fil för Sanitize. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Stänger fasaden. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Tar bort gammal xref med trailer och skapar en ny xref med trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Återställer dokumentet. Använd egenskaper för att anpassa. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Sparar den resulterande PDF-filen till en ström. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Sparar den resulterande PDF-filen till en fil. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Tar bort data efter sista %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Tar bort data före %PDF. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


