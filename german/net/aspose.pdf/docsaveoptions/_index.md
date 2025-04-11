---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions-Klasse. Speicheroptionen für den Export in das Doc-Format
type: docs
weight: 3750
url: /de/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions-Klasse

Speicheroptionen für den Export in das Doc-Format

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Verwenden Sie Absatz- oder Zeilenumbrüche |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Definiert die Batchgröße, wenn die batchweise Konvertierung für das Quell- und Zielformatpaar anwendbar ist. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftglykene während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in der Antwort geschlossen wird. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Ruft die Konvertierung für Type3-Schriften ab oder legt sie fest. Bei Type 3-Schriften müssen Glyphe durch Streams von Grafikoperatoren definiert werden. Das bedeutet, dass wir im DOC/DOCX-Ausgang Bilder anstelle von Text sehen. Setzen Sie dieses Flag auf true, um Type3-Schriften in TTF zu konvertieren und Text in der resultierenden Datei zu erhalten. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktion zum Extrahieren von Bildern oder Text für PDF-Dokumente mit OCR-Unterebene. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Ausgabeformat |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | X-Auflösung der konvertierten Bilder. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Y-Auflösung der konvertierten Bilder. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Dieser Parameter wird verwendet, um Textzeilen in Absätze zu gruppieren. Bestimmt, wie weit zwei relative Textzeilen auseinanderliegen können. Angegeben in Hundertsteln des Höhenmaßes der Textzeilen. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Definiert den Pfad (Dateiname oder Verzeichnisname) zur Speicherung temporärer Daten im Speicher-Speichermodus. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Erkennungsmodus. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Aktivieren Sie die Erkennung von Aufzählungszeichen |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | In PDF können Wörter innerlich mit Operatoren dargestellt werden, die Wörter durch das unabhängige Drucken ihrer Buchstaben oder Silben drucken. Um Wörter zu erkennen, müssen wir manchmal Gruppen von unabhängigen Zeichen erkennen, die in der Tat Wörter sind. Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben), die während der Erkennung von Wörtern im Quell-PDF als Abstand zwischen Wörtern behandelt werden müssen. (Das Vorhandensein von leerem Raum mit mindestens dieser Breite zwischen Buchstaben bedeutet, dass die Textelemente zu verschiedenen Wörtern gehören). Es ist normiert auf die Schriftgröße - 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes. ACHTUNG! Es wird nur in Fällen verwendet, in denen das Quell-PDF spezifische, selten verwendete Schriften enthält, für die der optimale Wert nicht aus der Schrift berechnet werden kann. In der überwiegenden Mehrheit der Fälle ändert dieser Parameter jedoch nichts im Ergebnisdokument. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Ruft das Verfahren zum erneuten Speichern von Schriften ab oder legt es fest. Wenn auf true gesetzt, laden wir Schriften auf jeder Seite neu, um den Einfluss vorheriger Schriftattribute zu vermeiden und die neu erstellte Schrift von Grund auf zu laden. Setzen Sie diese Option auf false, wenn Sie die Leistung verbessern möchten. Der Standardwert ist true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der Datenspeicherung. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherprozess wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherprozess eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Dieser Handler kann verwendet werden, um Fortschrittsereignisse der Konvertierung zu behandeln, z. B. kann er verwendet werden, um eine Fortschrittsanzeige oder Nachrichten über die aktuelle Anzahl der verarbeiteten Seiten anzuzeigen, ein Beispiel für den Code des Handlers, der den Fortschritt in der Konsole anzeigt, ist: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander platziert sind. In einem solchen Fall erzeugen Renderer der Zielformate (z. B. MsWord für das DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen von Hintergrundbildern, da ihre Techniken zur Glättung von Bildkanten (Anti-Aliasing) sich von denen des Acrobat Readers unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument sichtbare Grenzen zwischen Teilen derselben Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt zu beseitigen. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option daher bitte nur, wenn es wirklich notwendig ist. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in eine DOC- oder DOCX-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Schnittstelle [IPipelineOptions](../ipipelineoptions/)
* Namensraum [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)