---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions klass. Representerar alternativ för att ladda/importera TeX-fil till PDF-dokument
type: docs
weight: 10370
url: /sv/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions klass

Representerar alternativ för att ladda/importera TeX-fil till PDF-dokument.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Hämtar/anger ett visst värde för datum/tid primitiva som år, månad, dag och tid. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Hämtar/anger TeX inmatningskatalog. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Hämtar/anger namnet på jobbet. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Hämtar/anger en flagga som avbryter ligaturer i alla typsnitt. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Hämtar/anger TeX utmatningskatalog. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Hämtar/anger en flagga som tillåter att rasterisera matematiska formler. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Hämtar/anger flaggan som indikerar om det är nödvändigt att köra TeX-jobbet två gånger i fall, till exempel, det finns referenser i inmatnings-TeX-fil(er). Generellt är detta beteende användbart när motorn samlar in viss data under typografiprocessen och lagrar den i en hjälpfiler, allt vid första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Hämtar/anger TeX kräver inmatningskatalog. Obligatorisk inmatning är de filer som på något sätt ingår i huvud .tex-fil, t.ex. paket för vilka det inte finns något inbyggt stöd. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Hämtar/anger flaggan som indikerar om terminalutdata ska visas på konsolen. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Hämtar/anger flaggan som indikerar om typsnitt ska delas upp i utdatafilen eller inte. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och inläsningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall inläsningsoperationen ska upphöra. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Hämtar resultatet för TeX-laddning och kompilering - gick allt smidigt eller fanns det några kommentarer/fel. |

## Exempel

Följande exempel visar hur man konverterar TeX-fil till PDF-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)