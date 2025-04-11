---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSanitization-Klasse. Stellt die API für Sanitization und Wiederherstellung dar. Verwenden Sie sie, wenn Sie Dokumente auf keine andere Weise erstellen/öffnen können.
type: docs
weight: 4540
url: /de/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization-Klasse

Stellt die API für Sanitization und Wiederherstellung dar. Verwenden Sie sie, wenn Sie Dokumente auf keine andere Weise erstellen/öffnen können.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Nachdem die Datei gespeichert wurde, können Sie überprüfen, was mit der Datei gemacht wurde. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Ermöglicht die Erstellung eines neuen xref und Trailers für das Dokument. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Ermöglicht das Entfernen von Daten nach den PDF-Daten. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Ermöglicht das Entfernen von Daten vor den PDF-Daten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Bindet einen Pdf-Stream zur Sanitization. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Bindet eine Pdf-Datei zur Sanitization. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Schließt die Fassade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Entfernt das alte xref mit Trailer und erstellt ein neues xref mit Trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Stellt das Dokument wieder her. Verwenden Sie Eigenschaften zur Anpassung. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Speichert das Ergebnis-PDF im Stream. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Speichert das Ergebnis-PDF in einer Datei. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Entfernt Daten nach dem letzten %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Entfernt Daten vor %PDF. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)