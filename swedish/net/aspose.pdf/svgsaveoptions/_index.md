---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptions klass. Spara alternativ för export till SVG-format
type: docs
weight: 10230
url: /sv/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions klass

Spara alternativ för export till SVG-format

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Standardkonstruktör. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om teckensnittsglypher ska cachas medan aps-sidor förbereds. Förbättrar prestanda vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Denna attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Anger om utdata ska skapas som en zip-arkiv. Vänligen se kommentar till 'TreatTargetFileNameAsDirectory'-alternativ för att se reglerna för namngivning av svg-filer för sidor för fler-sidiga källdokument, som också tillämpas på den zippade uppsättningen av utdatafiler. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konvertering för anpassad hantering av skapade refererade externa bildfiler (som inbäddade BMP eller JPEG) inbäddade i sparad SVG. Den strategin måste bearbeta resurser och returnera en sträng som representerar önskad URI för den sparade resursen i den genererade SVG. Om bearbetning för denna eller den fil av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen ställ in i anpassad kod flaggan 'CustomProcessingCancelled' av 'imageSavingInfo'-parameterens variabel. Det signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om det inte fanns någon extern anpassad kod. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Anger om utdata-dokumentet ska skalas från typografiska punkter till pixlar. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Detta alternativ definierar om en målmapp (om den ännu inte finns) med samma namn som den begärda utdatafilen ska skapas istället för den begärda utdatafilen själv. Om så är fallet, kommer mappen att innehålla alla utdata SVG-bilder av sidor (som beskrivs nedan). Om inte, kommer utdatafiler för sidor andra än den första att skapas exakt i den begärda mappen som huvudutdatafil, men kommer att innehålla i filnamnet suffix _[2...n], som definieras av sidnummer, t.ex. om du definierar utdatafilen "C:\AsposeTests\output.svg" och utdata kommer att innehålla flera svg-filer av sidor, då kommer sidorna att skapas också i mappen "C:\AsposeTests\" och ha namnen 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF:er bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma mönstrade bakgrundsbilder som ligger nära varandra. I sådana fall genererar renderare av målformat (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delar av bakgrundsbilder, eftersom deras tekniker för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, vänligen försök använda denna inställning för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till en SVG-fil

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

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)