---
title: "Klass PdfSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PdfSaveOptions-klass. Sparaalternativ för export till Pdf-format"
type: docs
weight: 8570
url: /sv/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Spara alternativ för export till Pdf-format

```csharp
public class PdfSaveOptions : SaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Standardteckensnittets namn som används för teckensnitt som saknas på datorn. När PDF-dokumentet som sparas till PDF innehåller teckensnitt som inte är tillgängliga i själva dokumentet och på enheten, ersätter API:t dessa teckensnitt med standardteckensnittet (om ett teckensnitt med [`DefaultFontName`](./defaultfontname/) finns på enheten). |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Sökväg för temporära filer. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Exempel

Följande exempel visar hur man anger standardteckensnittets namn vid sparande av PDF.

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Läs in ett befintligt PDF-dokument med saknat teckensnitt
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Ange standardteckensnittets namn
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### Se även

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


