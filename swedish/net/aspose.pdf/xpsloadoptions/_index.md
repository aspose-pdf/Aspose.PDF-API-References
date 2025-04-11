---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsLoadOptions-klass. Representerar alternativ för att ladda/importera xps-fil till pdf-dokument
type: docs
weight: 11510
url: /sv/net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions klass

Representerar alternativ för att ladda/importera xps-fil till pdf-dokument.

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
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Definierar batchstorlek om batchkonvertering är tillämplig för käll- och destinationsformatpar. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller sätter flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformatet som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och laddningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall laddningsoperationen ska upphöra. |

## Exempel

Följande exempel visar hur man konverterar XPS-fil till PDF-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XPS File.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialize XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Save PDF file
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

### Se Även

* klass [LoadOptions](../loadoptions/)
* gränssnitt [IPipelineOptions](../ipipelineoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)