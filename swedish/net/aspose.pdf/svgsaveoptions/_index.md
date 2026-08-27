---
title: "Klass SvgSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.SvgSaveOptions-klass. Spara alternativ för export till SVG-format"
type: docs
weight: 10410
url: /sv/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

Sparaalternativ för export till SVG-format

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Anger om utdata ska skapas som ett zip‑arkiv. Se kommentaren till alternativet 'TreatTargetFileNameAsDirectory' för att se reglerna för namngivning av svg‑filer för sidor i ett flersidigt källdokument, som även tillämpas på den zip‑paketerade uppsättningen av utdatafiler. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade externa bildfiler (t.ex. inbäddade BMP‑ eller JPEG‑filer) som bäddas in i den sparade SVG‑filen. Strategin måste bearbeta resurser och returnera en sträng som representerar den önskade URI:n för den sparade resursen i den genererade SVG‑filen. Om bearbetning av denna eller den där filen av någon anledning måste utföras av konverterarens kod själv, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'imageSavingInfo'-parameter. Detta signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Anger om utgångsdokumentet ska skalas från typografiska punkter till pixlar. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Detta alternativ definierar om en målkatalog (om den ännu saknas) ska skapas med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla SVG‑bilder för sidor (som beskrivs nedan). Om alternativet är inaktiverat kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen som huvudutdatafil, men med filnamnssuffixet _[2...n] som bestäms av sidnumret, t.ex. om du definierar utdatafilen "C:\AsposeTests\output.svg" och utdata innehåller flera SVG‑filer för sidor, så kommer sidfilerna också att skapas i katalogen "C:\AsposeTests\" och ha namnen 'output.svg', 'output_2.svg', 'output_3.svg' osv. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

## Exempel

Följande exempel visar hur man konverterar en PDF‑fil till en SVG‑fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Sökvägen till din PDF‑fil.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// Sökvägen till utdata‑SVG‑filen.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initiera SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Spara SVG‑fil
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

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


