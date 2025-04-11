---
title: Class TeXSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXSaveOptions klass. Spara alternativ för export till TeX-format
type: docs
weight: 10400
url: /sv/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions klass

Spara alternativ för export till TeX-format

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller sätter ett booleanvärde som indikerar om teckensnittsglypher ska cachas medan aps-sidor förbereds. Förbättrar prestanda vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller sätter ett booleanvärde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Denna attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | Egenskap för _outDirectoryPath-parametern. |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | Returnerar antalet sidor efter konvertering. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | Lägger till en teckensnittskodning till listan över teckensnittskodningar |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | Rensar listan över teckensnittskodningar |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma mönstrade bakgrundsbilder som ligger nära varandra. I sådana fall genererar renderare av målformat (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delar av bakgrundsbilder, eftersom deras tekniker för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, vänligen försök att använda denna inställning för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd denna alternativ endast när det verkligen är nödvändigt. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till en TeX-fil

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

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)