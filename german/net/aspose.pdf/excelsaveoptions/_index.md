---
title: Class ExcelSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ExcelSaveOptions-Klasse. Speicheroptionen für den Export in das Excel-Format
type: docs
weight: 4080
url: /de/net/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions-Klasse

Speicheroptionen für den Export in das Excel-Format

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftglykene während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bildern oder Text für PDF-Dokumente mit OCR-Unterebene. |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | Ausgabeformat |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | Setzen Sie true, wenn Sie eine leere Spalte als erste Spalte des Arbeitsblatts einfügen möchten. Der Standardwert ist false; das bedeutet, dass keine leere Spalte eingefügt wird. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter in der resultierenden Arbeitsmappe minimieren möchten. Der Standardwert ist false; das bedeutet, dass jede PDF-Seite als separates Arbeitsblatt gespeichert wird. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der Datenspeicherung. |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | Setzen Sie true, um eine einheitliche Spaltenaufteilung im gesamten Dokument zu verwenden. Der Standardwert ist false; das bedeutet, dass die Spaltenaufteilung für jede Seite unabhängig ist. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherbetrieb wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherbetrieb eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander platziert sind. In solchen Fällen erzeugen Renderer der Zielformate (z. B. MsWord für das DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen von Hintergrundbildern, da ihre Techniken zur Glättung von Bildkanten (Anti-Aliasing) sich von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument sichtbare Grenzen zwischen Teilen derselben Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt loszuwerden. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option daher bitte nur, wenn es wirklich notwendig ist. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in eine XLS- oder XLSX-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// The path to output xls or xlsx File.
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ExcelSaveOptions	
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// Save xls or xlsx file
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)