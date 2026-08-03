---
title: "Klass EpubLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.EpubLoadOptions-klass. Innehåller alternativ för att läsa in/importera EPUB‑fil till pdf‑dokument"
type: docs
weight: 4170
url: /sv/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Innehåller alternativ för att läsa in/importera EPUB-fil till pdf-dokument.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Skapar standardalternativ för inläsning för att konvertera EPUB‑fil till pdf‑dokument. Standard pdf‑sidstorlek – A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Skapar inläsningsalternativ med angiven sidstorlek. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Hämtar eller anger den anpassade Css som ska tillämpas när Epub‑dokumentet öppnas. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Hämtar referens till objekt som representerar marginalinformation. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Hämtar eller anger utdata‑sidstorlek för import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Representerar användningsläge för marginalområdet – definierar behandlingen av instruktioner (om några) i CSS för det importerade dokumentet som rör användning av marginaler. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATTENTION! Funktionen är implementerad men har ännu inte publicerats i API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel‑dokumentet. Representerar användningsläge för sidstorlek under konvertering. Format (som HTML, EPUB osv.) har vanligtvis flytande layout, så de tillåter att anpassa till önskad sidstorlek. Men ibland har innehållet specificerade horisontella positioner eller storlek som hindrar att innehållet får plats i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet). |

## Exempel

Följande exempel visar hur man konverterar en EPUB‑fil till en PDF‑fil.

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din EPUB‑fil.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initiera EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Spara PDF‑fil
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

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


