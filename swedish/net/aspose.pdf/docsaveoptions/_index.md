---
title: "Klassen DocSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.DocSaveOptions klass. Spara alternativ för export till Doc-format"
type: docs
weight: 3870
url: /sv/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Spara alternativ för export till Doc-format.

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Använd stycke- eller radbrytningar |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Definierar batch-storlek om batch-konvertering är tillämplig för käll- och destinationsformatparet. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Hämtar eller anger konvertering för Type3-teckensnitt. I Type3-teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Det betyder att i DOC/DOCX-utdata ser vi bilder istället för text. Ställ in denna flagga till true för att konvertera Type3-teckensnitt till TTF och få text i den resulterande filen. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Utdataformat |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Konverterade bilders X-upplösning. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Konverterade bilders Y-upplösning. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av procent av textradernas höjd. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data när konvertering sker i minneslagringsläge. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Identifieringsläge. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Aktivera identifiering av punktlistor. |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | I Pdf kan ord internt representeras med operators som skriver ut ord genom att oberoende skriva ut deras letters eller syllables. Så för att upptäcka ord måste vi ibland identifiera grupper av oberoende chars som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (letters, syllables) som ska behandlas som avstånd mellan ord under identifiering av ord i käll-Pdf. (Närvaro av ett tomt utrymme minst lika brett som detta mellan letters betyder att textelementen tillhör olika ord). Den är normaliserad till font size – 1,0 betyder 100 % av det antagna ordets font size. ATTENTION! Den används endast i fall då käll-Pdf innehåller specifika sällan använda fonts för vilka det optimala värdet inte kan beräknas från font. Så i de allra flesta fall förändrar denna parameter inget i det resulterande dokumentet. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Hämtar eller anger proceduren för att spara om fonts. Om den sätts till true laddar vi om fonts på varje sida för att undvika påverkan från tidigare font-egenskaper och laddar det nyss skapade fontet från början. Ställ in detta alternativ till false om du vill förbättra prestanda. Standardvärdet är true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor. Exempel på hanterarens kod som visar förloppet i konsolen är: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

### Exempel

Följande exempel visar hur man konverterar PDF-fil till DOC- eller DOCX-fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Sökvägen till din PDF‑fil.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// Sökvägen till utdata-DOC- eller DOCX-fil.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Ställ in identifieringsläget som Flöde
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Ställ in horisontell närhet till 2.5
			RelativeHorizontalProximity = 2.5f,
			// Aktivera värdet för att känna igen punkter under konverteringsprocessen
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

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


