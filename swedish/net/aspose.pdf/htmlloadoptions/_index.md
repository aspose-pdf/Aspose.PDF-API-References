---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlLoadOptions klass. Representerar alternativ för att ladda/importera html-fil till pdf-dokument
type: docs
weight: 5530
url: /sv/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions klass

Representerar alternativ för att ladda/importera html-fil till pdf-dokument.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Skapar laddningsalternativ för att konvertera html till pdf-dokument med tom basväg. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Skapar laddningsalternativ för att konvertera html till pdf-dokument med definierad basväg. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Basvägen/url för html-filen. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller ställer in flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Hämtar eller ställer in möjliga mediatyper som används under rendering. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Hämtar eller ställer in attributet som specificerar kodningen som används för detta dokument vid tidpunkten för analysen. Om detta attribut är null kommer kodningen att bestämmas från dokumentets teckenuppsättning. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Hämtar eller ställer in typsnittens inbäddning i resultatdokumentet |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Hämtar eller ställer in flaggan som specificerar att @page-regler definierade i css kommer att åsidosätta värden som definieras i PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Hämtar eller ställer in rendering av hela dokumentet till en enda sida |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformatet som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Hämtar eller ställer in dokumentets sidinformation |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Hämtar eller ställer in layoutalternativ. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och laddningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall laddningsoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Ibland är det nödvändigt att undvika användning av intern laddare av externa resurser (som bilder eller CSS) och tillhandahålla en anpassad metod som kommer att hämta begärda resurser från någonstans. Till exempel, under användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig: i sådana fall bör viss anpassad kod sättas in i en speciell metod, och en delegerad som hänvisar till den metoden bör tilldelas detta attribut. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Om inläsning av externa data som refereras i HTML kräver autentisering kan du lägga dem i denna parameter - de kommer att användas under inläsning av externa resurser |

## Exempel

Följande exempel visar hur man konverterar HTML-fil till PDF-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
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

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)