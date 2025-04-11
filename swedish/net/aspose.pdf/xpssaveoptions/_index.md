---
title: Class XpsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsSaveOptions klass. Spara alternativ för export till Xps-format
type: docs
weight: 11520
url: /sv/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions klass

Spara alternativ för export till Xps-format

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
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | Definierar batchstorlek om batchkonvertering är tillämplig för käll- och destinationsformatpar. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om teckensnittsglypher ska cachas medan aps-sidor förbereds. Förbättrar prestanda vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Denna attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Indikerar om transparent (OCR:ad) text ska bevaras. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma mönstrade bakgrundsbilder placerade nära varandra. I sådana fall genererar renderare av målformat (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delar av bakgrundsbilder, eftersom deras tekniker för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, vänligen försök att använda denna inställning för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd denna alternativ endast när det verkligen är nödvändigt. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till en XPS-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// The path to your XPS File
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize XpsSaveOptions	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// Save XPS file
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

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* gränssnitt [IPipelineOptions](../ipipelineoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)