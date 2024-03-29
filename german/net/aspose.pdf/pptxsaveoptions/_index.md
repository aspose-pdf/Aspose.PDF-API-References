---
title: PptxSaveOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: Speicheroptionen für den Export in das SVG-Format
type: docs
weight: 6140
url: /de/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

Speicheroptionen für den Export in das SVG-Format

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, dass das Antwortobjekt geschlossen wird, nachdem das Dokument in der Antwort gespeichert wurde. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler) { get; set; } | Dieser Handler kann verwendet werden, um Konvertierungsfortschrittsereignisse zu verarbeiten z. B. kann er verwendet werden, um Fortschrittsbalken oder Meldungen über die aktuelle Menge verarbeiteter Seiten anzuzeigen. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bild oder Text für PDF-Dokumente mit OCR-Unterebene. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution) { get; set; } | Holt oder setzt die Bildauflösung (dpi). Standard ist 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes) { get; set; } | Schaltet die Erkennung von Textspalten um |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format der Datenspeicherung. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages) { get; set; } | Wenn auf true gesetzt, werden Bilder von allen anderen Grafiken getrennt |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages) { get; set; } | Wenn auf „true“ gesetzt, wird der gesamte Inhalt als Bilder erkannt (eines pro Seite) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Rückruf zur Behandlung von generierten Warnungen. Der WarningHandler gibt das ReturnAction-Aufzählungselement zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abbrechen zurückgeben, in diesem Fall sollte der Speichervorgang beendet werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen) die aus mehreren, nebeneinander angeordneten, gleichen Hintergrundbildern bestehen. In solchen Fällen erzeugen Renderer von Zielformaten (z. B. MsWord für DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen von Hintergrundbildern , weil sich ihre Techniken der Bildkantenglättung (Anti-Aliasing) von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen derselben Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um davon zu befreien unerwünschte Wirkung. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, also verwenden Sie diese Option bitte nur, wenn es wirklich notwendig ist. |

### Siehe auch

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
