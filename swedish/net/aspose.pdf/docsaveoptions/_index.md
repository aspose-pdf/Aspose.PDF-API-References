---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions klass. Spara alternativ för export till Doc-format
type: docs
weight: 3750
url: /sv/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions klass

Spara alternativ för export till Doc-format

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Standardkonstruktör. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Använd stycke- eller radbrytningar |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Definierar batchstorlek om batchkonvertering är tillämplig för käll- och destinationsformatpar. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller ställer in ett booleskt värde som indikerar om teckensnittsglypher ska cachas medan aps-sidor förbereds. Förbättrar prestandan vid konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller ställer in ett booleskt värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Hämtar eller ställer in konvertering för Type3-teckensnitt. I Type 3-teckensnitt ska glypher definieras av strömmar av grafikoperatörer. Detta innebär att vi i DOC/DOCX-utdata ser bilder istället för text. Sätt detta flagga till true för att konvertera Type3-teckensnitt till TTF och få text i den resulterande filen. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Denna attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Utdataformat |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Konverterade bilders X-upplösning. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Konverterade bilders Y-upplösning. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av textradernas höjd. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Definierar sökvägen (filnamn eller katalognamn) för att hålla temporära data när konvertering sker i minnesbesparande läge. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Kännedomsläge. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Aktivera igenkänning av punkter |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | I Pdf kan ord inre representeras med operatörer som skriver ord genom att oberoende skriva deras bokstäver eller stavelser. Så, för att upptäcka ord behöver vi ibland upptäcka grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på utrymmet mellan textelement (bokstäver, stavelser) som måste behandlas som avstånd mellan ord under igenkänning av ord i käll-PDF. (Närvaron av tomt utrymme med minst denna bredd mellan bokstäver betyder att textuella element tillhör olika ord). Det är normerat till teckensnittsstorlek - 1.0 betyder 100% av den förväntade ordets teckensnittsstorlek. OBS! Det används endast i fall där käll-PDF innehåller specifika sällan använda teckensnitt för vilka optimalt värde inte kan beräknas från teckensnittet. Så, i de flesta fall förändrar denna parameter ingenting i resultatdokumentet. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Hämtar eller ställer in proceduren för att spara om teckensnitt. Om det är inställt på true, laddar vi om teckensnitt på varje sida för att undvika påverkan av tidigare teckensnittsinställningar och laddar det nyss skapade teckensnittet från grunden. Sätt detta alternativ till false om du vill förbättra prestandan. Standardvärdet är true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och sparaoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall sparaoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Denna hanterare kan användas för att hantera konverteringsframstegshändelser, t.ex. den kan användas för att visa en framstegsindikator eller meddelanden om aktuellt antal bearbetade sidor, exempel på hanterarens kod som visar framsteg på konsolen är: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF:er bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma mönstrade bakgrundsbilder som ligger nära varandra. I sådana fall genererar renderare av målformat (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delar av bakgrundsbilder, eftersom deras tekniker för att mjuka upp bildkanter (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, vänligen försök att använda denna inställning för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

### Exempel

Följande exempel visar hur man konverterar en PDF-fil till DOC- eller DOCX-fil

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

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* gränssnitt [IPipelineOptions](../ipipelineoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)