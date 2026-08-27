---
title: "Class MhtLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.MhtLoadOptions class. Representerar alternativ för inläsning/import av .mhtfil till pdf-dokument"
type: docs
weight: 7110
url: /sv/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions class

Representerar alternativ för laddning/import av .mht-fil till pdf-dokument.

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | Hämtar eller anger sidinformation för dokumentet |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Exempel

Följande exempel visar hur man konverterar en MHT-fil till en PDF-fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din MHT-fil.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initiera MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Spara PDF‑fil
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


