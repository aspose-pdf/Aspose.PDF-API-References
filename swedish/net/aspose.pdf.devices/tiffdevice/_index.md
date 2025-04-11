---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TiffDevice class. This class helps to save pdf document page by page into the one tiff image
type: docs
weight: 3700
url: /sv/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice klass

Denna klass hjälper till att spara pdf-dokument sida för sida i en tiff-bild.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Initierar en ny instans av klassen `TiffDevice` med standardinställningar. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av klassen `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av klassen `TiffDevice`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Hämtar eller sätter renderingalternativ. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Hämtar inställningar för att mappa pdf till tiff-bild. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Hämtar bildens utdatabredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Utför Bradley-binarisering för inmatningsström. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Bearbetar hela dokumentet och sparar resultat i strömmen. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Bearbetar hela dokumentet och sparar resultat i filen. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultat i filen. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Konverterar vissa dokument sidor till tiff och sparar det i utdataströmmen. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Bearbetar vissa sidor av dokumentet och sparar resultat i filen. |

## Exempel

Följande exempel visar hur man konverterar PDF-fil till TIFF-bilder.

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
	}
```

```csharp
[VB.NET]

    ' The path to your PDF Directory
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The file name of the PDF
    Dim pdfFile As String = "YOUR_PDF_FILE"
 
    ' Initialize instance of Document class 
	Using pdfDocument As Document = New Document(Path.Combine(dataDir, pdfFile))
	
		' Create Resolution object  
		Dim resolution As Resolution = New Resolution(300)
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### Se Även

* klass [DocumentDevice](../documentdevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* samling [Aspose.PDF](../../)