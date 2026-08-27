---
title: "Klass PptxSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PptxSaveOptions-klass. Spara alternativ för export till SVG-format"
type: docs
weight: 9630
url: /sv/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

Sparaalternativ för export till SVG-format

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor. Exempel på hanterarens kod som visar förloppet i konsolen är: |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Hämtar eller anger bildens upplösning (dpi). Standard är 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Växlar igenkänning av textkolumner |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Om den är satt till true separeras bilder från all annan grafik |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Om den är satt till true känns allt innehåll igen som bilder (en per sida) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

## Exempel

Följande exempel visar hur man konverterar PDF‑fil till PPT‑ eller PPTX‑fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Sökvägen till din PDF‑fil.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// Sökvägen till din PPT‑ eller PPTX‑fil.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initiera PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Spara PPT‑ eller PPTX‑fil
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


