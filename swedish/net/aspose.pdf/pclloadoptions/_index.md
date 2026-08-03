---
title: "Klass PclLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PclLoadOptions-klass. Representerar alternativ för att läsa in PCL-fil i pdf-dokument"
type: docs
weight: 8440
url: /sv/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions class

Representerar alternativ för att ladda (importera) PCL-fil till ett pdf-dokument.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Definierar batch-storlek om batch-konvertering är tillämplig för käll- och destinationsformatparet. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Definierar konverteringsmotor som kommer att användas för konvertering |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Lista över konverteringsfel. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Hämtar eller anger ett booleskt värde som indikerar om PCL-konverteringsfel ska undertryckas. |

## Exempel

Följande exempel visar hur man konverterar en PCL-fil till en PDF-fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din PCL-fil.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initiera PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Spara PDF‑fil
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se även

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


