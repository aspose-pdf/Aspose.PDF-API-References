---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions klass. Innehåller alternativ för att ladda/importera EPUB-fil till pdf-dokument
type: docs
weight: 4050
url: /sv/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions klass

Innehåller alternativ för att ladda/importera EPUB-fil till pdf-dokument.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Skapar standardladdningsalternativ för att konvertera EPUB-fil till pdf-dokument. Standard pdf-sidstorlek - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Skapar laddningsalternativ med angiven sidstorlek. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Hämtar eller ställer in den anpassade Css som ska tillämpas när Epub-dokumentet öppnas. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller ställer in flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Hämtar referens till objekt som representerar marginalinformation. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Hämtar eller ställer in utmatningssidstorlek för import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-objekt som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och laddningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall laddningsoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Representerar användningsläge för marginalområdet - definierar behandlingen av instruktioner (om några) från CSS i det importerade dokumentet relaterat till användningen av marginaler. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | UPPMÄRKSAMHET! Funktionen är implementerad men har ännu inte lagts till i den offentliga API:et eftersom blockerande problem i OSHARED-lagret avslöjades för exempel-dokument. Representerar användningsläge för sidstorlek under konvertering. Format (som HTML, EPUB etc), har vanligtvis flytande design, så det tillåter att passa den erforderliga sidstorleken. Men ibland har innehållet angivna horisontella positioner eller storlek som inte tillåter att placera innehållet i den erforderliga sidstorleken. I sådana fall kan vi definiera vad som ska göras i detta fall (dvs när storleken på innehållet inte passar den erforderliga initiala sidstorleken för det resulterande PDF-dokumentet). |

## Exempel

Följande exempel visar hur man konverterar EPUB-fil till PDF-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)