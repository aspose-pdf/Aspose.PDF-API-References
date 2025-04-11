---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsSaveOptions-Klasse. Speicheroptionen für den Export in das PS PostScript- oder EPS-Format
type: docs
weight: 9740
url: /de/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions-Klasse

Speicheroptionen für den Export in das PS (PostScript) oder EPS-Format.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | Konstruktor. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftart-Glyphen während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | Ruft ein Flag ab oder legt es fest, das angibt, ob Schriftarten im resultierenden PS-Dokument eingebettet werden müssen. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | Ruft den Typ ab oder legt ihn fest, in dem Schriftarten im resultierenden PS-Dokument eingebettet werden müssen. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bildern oder Text für PDF-Dokumente mit OCR-Unterlagen. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der gespeicherten Daten. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherprozess wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherprozess eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer der Zielformate (z. B. MsWord für das DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen der Hintergrundbilder, da ihre Techniken zur Glättung von Bildkanten (Anti-Aliasing) sich von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument sichtbare Grenzen zwischen Teilen der gleichen Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt loszuwerden. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option daher bitte nur, wenn es wirklich notwendig ist. |

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)