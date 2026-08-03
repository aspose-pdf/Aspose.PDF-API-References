---
title: "Klass HtmlLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlLoadOptions-klass. Representerar alternativ för att ladda/importera HTML-fil till PDF-dokument"
type: docs
weight: 5660
url: /sv/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

Representerar alternativ för att läsa in/ importera html-fil till pdf-dokument.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Skapar laddningsalternativ för att konvertera HTML till PDF-dokument med tom basväg. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Skapar laddningsalternativ för att konvertera HTML till PDF-dokument med definierad basväg. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Basvägen/URL för html-filen. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Hämtar eller anger möjliga mediatyper som används under rendering. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Hämtar eller anger attributet som specificerar kodningen som används för detta dokument vid parsning. Om detta attribut är null bestäms kodningen från dokumentets teckenuppsättning. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Hämtar eller anger inbäddning av teckensnitt i resulterande dokument |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Hämtar eller anger flaggan som specificerar att @page-regler definierade i CSS kommer att åsidosätta värden definierade i PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Hämtar eller anger rendering av hela dokumentet till en enda sida |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Hämtar eller anger sidinformation för dokumentet |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Hämtar eller anger layoutalternativ. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig: i sådant fall bör viss anpassad kod som placeras i en speciell metod användas, och en delegat som refererar till den metoden bör tilldelas detta attribut. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Om laddning av externa data som refereras i HTML kräver autentiseringsuppgifter kan du ange dem i denna parameter – de kommer att användas vid laddning av externa resurser |

## Exempel

Följande exempel visar hur man konverterar en HTML-fil till en PDF-fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din HTML-fil.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initiera HtmlLoadOptions\t
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Spara PDF‑fil
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


