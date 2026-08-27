---
title: "Klass XpsLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XpsLoadOptions klass. Representerar alternativ för att ladda/importera xps-fil till pdf dokument."
type: docs
weight: 11700
url: /sv/net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions class

Representerar alternativ för att läsa in/importera xps‑fil till pdf‑dokument.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Definierar batch-storlek om batch-konvertering är tillämplig för käll- och destinationsformatparet. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Exempel

Följande exempel visar hur man konverterar XPS-fil till PDF-fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din XPS-fil.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initiera XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Spara PDF‑fil
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se även

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


