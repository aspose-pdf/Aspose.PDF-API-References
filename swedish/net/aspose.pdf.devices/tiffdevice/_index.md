---
title: "Klass TiffDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.TiffDevice-klass. Denna klass hjälper till att spara PDF‑dokument sida för sida i en tiff‑bild"
type: docs
weight: 3820
url: /sv/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

Denna klass hjälper till att spara PDF-dokumentets sidor en efter en i en enda TIFF-bild.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Initierar en ny instans av `TiffDevice`-klassen med standardinställningar. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av `TiffDevice`-klassen. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initierar en ny instans av `TiffDevice`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Hämtar eller anger formulärets presentationsläge. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Hämtar eller anger renderingsalternativ. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Hämtar inställningar för mappning av PDF till tiff‑bild. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Utför Bradley-binarisering för inmatningsström. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Bearbetar hela dokumentet och sparar resultatet i en ström. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Bearbetar hela dokumentet och sparar resultatet i en fil. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Konverterar vissa dokumentsidor till TIFF och sparar dem i utdataströmmen. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Bearbetar vissa sidor i dokumentet och sparar resultatet i en fil. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till TIFF-bilder.

```csharp
[C#]
	// Sökvägen till din PDF-katalog
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Filnamnet på PDF-filen
	string pdfFile = @"YOUR_PDF_FILE";

	// Initiera en instans av Document-klassen
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Skapa Resolution-objekt \t
		Resolution resolution = new Resolution(300);
		
		// Skapa TiffSettings-objekt
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Skapa TIFF-enhet
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Konvertera ett PDF-dokument till en TIFF-bild
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

### Se även

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


