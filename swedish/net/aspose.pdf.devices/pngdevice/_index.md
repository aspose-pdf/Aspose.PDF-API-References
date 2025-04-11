---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.PngDevice klass. Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i png
type: docs
weight: 3650
url: /sv/net/aspose.pdf.devices/pngdevice/
---
## PngDevice klass

Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Initierar en ny instans av `PngDevice` klassen med standardupplösning. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Initierar en ny instans av `PngDevice` klassen med angiven sidstorlek, standardupplösning (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Initierar en ny instans av `PngDevice` klassen. Upplösning för den resulterande bildfilen, se [`Resolution`](../resolution/) klass. |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Initierar en ny instans av `PngDevice` klassen med angivna bilddimensioner, standardupplösning (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av `PngDevice` klassen med angiven sidstorlek och upplösning. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av `PngDevice` klassen med angivna bilddimensioner och upplösning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller sätter sidkoordinattyp (Media/Crop boxar). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller sätter renderingalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Hämtar eller sätter om bilden har transparent bakgrund. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Konverterar sidan till png och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till PNG-bilder.

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

		// Initialize PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Close stream
				pngStream.Close();
			}
		}
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
		' initialize PngDevice  

		Dim pngDevice As PngDevice = New PngDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using pngStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.png", FileMode.Create)
				' Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages(pageCount), pngStream)

				' Close stream
				pngStream.Close()
			End Using
		Next
	End Using
```

### Se Även

* klass [ImageDevice](../imagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* sammansättning [Aspose.PDF](../../)