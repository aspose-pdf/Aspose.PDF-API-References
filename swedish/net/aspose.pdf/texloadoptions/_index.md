---
title: "Klass TeXLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.TeXLoadOptions-klass. Representerar alternativ för att läsa in/importera TeX-fil till PDF-dokument"
type: docs
weight: 10550
url: /sv/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

Representerar alternativ för att läsa in/importera TeX‑fil till PDF‑dokument.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Hämtar/sätter ett visst värde för datum/tid‑primitiver som år, månad, dag och tid. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Hämtar/sätter TeX‑indatakatalog. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Hämtar/sätter namnet på jobbet. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Hämtar/sätter en flagga som avbryter ligaturer i alla teckensnitt. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Hämtar/sätter TeX‑utdatakatalog. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Hämtar/sätter en flagga som tillåter rasterisering av matematiska formler. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Hämtar/sätter flaggan som anger om det är nödvändigt att köra TeX‑jobbet två gånger i fall, till exempel, det finns referenser i indata‑TeX‑fil(er). I allmänhet är detta beteende användbart när motorn samlar in data under typografiprocessen och lagrar den i en hjälpfil under första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Hämtar/sätter TeX‑krävd indata‑katalog. Krävda indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket för vilka det inte finns inbyggt stöd. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Hämtar/sätter flaggan som anger om terminalutdata ska visas i konsolen. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Hämtar/sätter flaggan som anger om teckensnitt ska delmängdas i utdatafilen eller inte. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Hämtar resultatet för TeX‑laddning och kompilering – gick allt smidigt eller fanns det några kommentarer/fel. |

## Exempel

Följande exempel visar hur man konverterar en TeX‑fil till en PDF‑fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din TeX‑fil.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initiera TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Spara PDF‑fil
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

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


