---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MarkdownSaveOptions-Klasse. Stellt die Dokumentenspeicheroptionenklasse im Markdown-Format dar
type: docs
weight: 6910
url: /de/net/aspose.pdf/markdownsaveoptions/
---
## Klasse MarkdownSaveOptions

Stellt die Dokumentenspeicheroptionenklasse im Markdown-Format dar.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Holt oder setzt ein rechteckiges Gebiet, um Inhalte in Markdown zu extrahieren. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Holt oder setzt einen booleschen Wert, der angibt, ob Schriftglys cached werden, während APS-Seiten vorbereitet werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Holt oder setzt einen booleschen Wert, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Holt oder setzt den Stil der Betonung für das generierte Dokument. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bildern oder Text für PDF-Dokumente mit OCR-Unterebene. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Holt und setzt eine Eigenschaft, die angibt, ob Vektorgrafiken extrahiert werden sollen. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Definiert die erwarteten Überschriftsebenen, die in der Schriftgrößenerkennung verwendet werden sollen. Wenn dieser Eigenschaftswert gesetzt ist, wird die Überschriftenerkennung !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic Strategie ausgewählt, wenn die !:PdfToMarkdown.HeadingRecognitionStrategy.Auto Strategien gesetzt sind, selbst wenn das Dokument Lesezeichen enthält. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Holt oder setzt die Strategie zur Überschriftenerkennung. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Holt oder setzt den Überschriftstil für das generierte Dokument. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Holt oder setzt den Zeilenumbruchstil für das generierte Dokument. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Holt und setzt den Verzeichnisnamen zum Speichern von Dokumentressourcen wie Bildern. Wenn der Wert nicht angegeben ist, werden die Bilder im selben Verzeichnis wie die Markdown-Datei selbst gespeichert. Dies ist kein Pfad, es ist nur ein Name! Dieses Verzeichnis wird automatisch im Verzeichnis mit der gespeicherten Markdown-Datei erstellt. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der Datenspeicherung. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Holt und setzt die Erlaubnis zur Umwandlung von tiefgestellten und hochgestellten Zeichen. Dieser Wert ist standardmäßig wahr. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Holt und setzt die Erlaubnis zur Verwendung eines img-Tags, um Bilder links und rechts vom Text einzufügen. In diesem Fall wird der Text im Markdown-Viewer um das Bild gewickelt. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherbetrieb wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherbetrieb eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer der Zielformate (z.B. MsWord für das DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen von Hintergrundbildern, da ihre Techniken zur Glättung von Bildkanten (Anti-Aliasing) sich von Acrobat Reader unterscheiden. Wenn es so aussieht, als würde das exportierte Dokument sichtbare Grenzen zwischen Teilen derselben Hintergrundbilder enthalten, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt loszuwerden. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option daher bitte nur, wenn es wirklich notwendig ist. |

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)