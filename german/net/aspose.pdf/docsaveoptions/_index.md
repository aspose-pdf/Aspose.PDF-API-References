---
title: DocSaveOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: Speicheroptionen für den Export in das Doc-Format
type: docs
weight: 1840
url: /de/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Speicheroptionen für den Export in das Doc-Format

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DocSaveOptions](docsaveoptions)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend) { get; set; } | Absatz- oder Zeilenumbrüche verwenden |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize) { get; set; } | Definiert die Stapelgröße, wenn eine Stapelkonvertierung anwendbar ist in ein Paar aus Quell- und Zielformaten. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, dass das Antwortobjekt geschlossen wird, nachdem das Dokument in der Antwort gespeichert wurde. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bild oder Text für PDF-Dokumente mit OCR-Unterebene. |
| [Format](../../aspose.pdf/docsaveoptions/format) { get; set; } | Ausgabeformat |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx) { get; set; } | Konvertierte Bilder X-Auflösung. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony) { get; set; } | Konvertierte Bilder Y-Auflösung. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines) { get; set; } | Dieser Parameter dient zum Gruppieren von Textzeilen zu Absätzen. Bestimmt, wie weit zwei relative Textzeilen voneinander entfernt sein dürfen. Angabe in hundert Prozent der Textzeilenhöhe. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath) { get; set; } | Definiert den Pfad (Dateiname oder Verzeichnisname) zum Halten temporärer Daten beim Konvertieren im Speichersparmodus. |
| [Mode](../../aspose.pdf/docsaveoptions/mode) { get; set; } | Erkennungsmodus. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets) { get; set; } | Aufzählungszeichenerkennung einschalten |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity) { get; set; } | In Pdf können Wörter innerlich mit Operatoren dargestellt werden, die words drucken, indem sie unabhängig ihre Buchstaben oder Silben drucken. Um also Wörter zu erkennen, müssen wir manchmal Gruppen von unabhängigen Zeichen erkennen, die tatsächlich Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben) , die bei der Erkennung von Wörtern im Quell-PDF als Abstand zwischen Wörtern behandelt werden müssen . (das Vorhandensein von Leerzeichen zumindest bei dieser Breite zwischen den Buchstaben bedeutet, dass Textelemente zu verschiedenen Wörtern gehören). Es ist auf die Schriftgröße normiert - 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes. ACHTUNG! Wird nur in Groß- und Kleinschreibung verwendet wenn Quell-PDF bestimmte selten verwendete Schriftarten enthält, für die der optimale Wert nicht aus der Schriftart berechnet werden kann. In den allermeisten Fällen ändert dieser Parameter also nichts am Ergebnisdokument. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format der Datenspeicherung. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Rückruf zur Behandlung von generierten Warnungen. Der WarningHandler gibt das ReturnAction-Aufzählungselement zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abbrechen zurückgeben, in diesem Fall sollte der Speichervorgang beendet werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler) | Dieser Handler kann verwendet werden, um Konvertierungsfortschrittsereignisse zu verarbeiten z. B. kann er verwendet werden, um Fortschrittsbalken oder Meldungen über die aktuelle Menge verarbeiteter Seiten anzuzeigen. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen) die aus mehreren, nebeneinander angeordneten, gleichen Hintergrundbildern bestehen. In solchen Fällen erzeugen Renderer von Zielformaten (z. B. MsWord für DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen von Hintergrundbildern , weil sich ihre Techniken der Bildkantenglättung (Anti-Aliasing) von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen derselben Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um davon zu befreien unerwünschte Wirkung. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, also verwenden Sie diese Option bitte nur, wenn es wirklich notwendig ist. |

### Siehe auch

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
