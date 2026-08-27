---
title: "Class XpsSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XpsSaveOptions class. Spara alternativ för export till Xps-format"
type: docs
weight: 11710
url: /sv/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Spara alternativ för export till Xps‑format

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | Definierar batch-storlek om batch-konvertering är tillämplig för käll- och destinationsformatparet. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | Hämtar/anger standardtypsnittets namn. Används om det inbäddade typsnittets namn inte hittas i systemet. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Indikerar om transparent (OCR:ad) text ska bevaras. |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | Hämtar/anger flaggan för att använda inbäddade TrueType-typsnitt. Att undvika användning av inbäddade TrueType-typsnitt kan minska konverteringstiden. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till en XPS-fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Sökvägen till din PDF-fil
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// Sökvägen till din XPS-fil
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initiera XpsSaveOptions	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// Spara XPS-fil
		pdfDocument.Save(xpsFile, saveOptions);
	}
```

```csharp
[VB.NET]
 
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf")

    ' The path to your XPS File
    Dim xpsFile = Path.Combine(dataDir, "PDF-to-XPS.xps")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XpsSaveOptions
        Dim saveOptions As XpsSaveOptions = New XpsSaveOptions()
 
        ' Save XPS file
        pdfDocument.Save(xpsFile, saveOptions)
    End Using
```

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


