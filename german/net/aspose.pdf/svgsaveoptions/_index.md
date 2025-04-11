---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptions-Klasse. Speicheroptionen für den Export im SVG-Format
type: docs
weight: 10230
url: /de/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions-Klasse

Speicheroptionen für den Export im SVG-Format

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftglykene während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bildern oder Text für PDF-Dokumente mit OCR-Unterlayer. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der Datenspeicherung. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rückruf zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherprozess wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherprozess eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Gibt an, ob die Ausgabe als ein ZIP-Archiv erstellt wird. Bitte beachten Sie den Kommentar zu den Optionen 'TreatTargetFileNameAsDirectory', um die Regeln zur Benennung der SVG-Dateien von Seiten für mehrseitige Quelldokumente zu sehen, die auch auf das gezippte Set von Ausgabedateien angewendet werden. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Dieses Feld kann eine Speicherstrategie enthalten, die während der Konvertierung verwendet werden muss (falls vorhanden) für die benutzerdefinierte Handhabung der erstellten referenzierten externen Bilddateien (wie eingebettete BMP oder JPEG), die in das gespeicherte SVG eingebettet sind. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URI der gespeicherten Ressource im generierten SVG darstellt. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Gibt an, ob das Ausgabedokument von typografischen Punkten in Pixel skaliert werden soll. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Diese Option definiert, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei anstelle der angeforderten Ausgabedatei selbst erstellt wird. Wenn ja, enthält dieses Verzeichnis alle Ausgab SVG-Bilder der Seiten (wie unten beschrieben). Wenn nicht, werden die Ausgabedateien der Seiten, die nicht die erste sind, genau im angeforderten Verzeichnis wie die Hauptausgabedatei erstellt, enthalten jedoch im Dateinamen den Suffix _[2...n], der durch die Seitennummer definiert ist, z.B. wenn Sie die Ausgabedatei "C:\AsposeTests\output.svg" definieren und die Ausgabe mehrere SVG-Dateien von Seiten enthält, dann werden die Dateien der Seiten auch im Verzeichnis "C:\AsposeTests\" erstellt und haben die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander angeordnet sind. In einem solchen Fall erzeugen Renderer der Zielformate (z.B. MsWord für DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen der Hintergrundbilder, da ihre Techniken zur Glättung der Bildkanten (Anti-Aliasing) sich von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument sichtbare Grenzen zwischen Teilen der gleichen Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt loszuwerden. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option daher bitte nur, wenn es wirklich notwendig ist. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in eine SVG-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)