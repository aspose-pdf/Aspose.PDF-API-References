---
title: Class TeXSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXSaveOptions-Klasse. Speicheroptionen für den Export im TeX-Format
type: docs
weight: 10400
url: /de/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions-Klasse

Speicheroptionen für den Export im TeX-Format

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftglykene während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bildern oder Text für PDF-Dokumente mit OCR-Unterlayer. |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | Eigenschaft für den Parameter _outDirectoryPath. |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | Gibt die Anzahl der Seiten nach der Konvertierung zurück. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der Datenspeicherung. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rückruf zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherprozess wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherprozess eingestellt werden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | Fügt eine Schriftartkodierung zur Liste der Schriftartkodierungen hinzu |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | Löscht die Liste der Schriftartkodierungen |

## Felder

| Name | Beschreibung |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander platziert sind. In solchen Fällen erzeugen Renderer der Zielformate (z.B. MsWord für das DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen der Hintergrundbilder, da ihre Techniken zur Glättung von Bildkanten (Anti-Aliasing) sich von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen der gleichen Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt loszuwerden. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option daher bitte nur, wenn es wirklich notwendig ist. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in eine TeX-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// The path to output TeX File.
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// Save TeX file
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)