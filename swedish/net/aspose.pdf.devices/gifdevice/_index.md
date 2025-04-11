---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.GifDevice klass. Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i gif
type: docs
weight: 3600
url: /sv/net/aspose.pdf.devices/gifdevice/
---
## GifDevice klass

Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Initierar en ny instans av `GifDevice` klassen med standardupplösning. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Initierar en ny instans av `GifDevice` klassen med angiven sidstorlek, standardupplösning (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Initierar en ny instans av `GifDevice` klassen. Upplösning för den resulterande bildfilen, se [`Resolution`](../resolution/) klass. |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Initierar en ny instans av `GifDevice` klassen med angivna bilddimensioner, standardupplösning (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av `GifDevice` klassen med angiven sidstorlek och upplösning. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av `GifDevice` klassen med angivna bilddimensioner och upplösning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller sätter sidkoordinattype (Media/Crop boxes). CropBox-värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller sätter formulärpresentationläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller sätter renderingalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Konverterar sidan till gif och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till GIF-bilder.

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

		// Initialize GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Close stream
				gifStream.Close();
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
	
		' Initialize GifDevice  
		Dim gifDevice As GifDevice = New GifDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using gifStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.gif", FileMode.Create)
		   
				' Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages(pageCount), gifStream)

				' Close stream
				gifStream.Close()
			End Using
		Next
	End Using
```

### Se Även

* klass [ImageDevice](../imagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* samling [Aspose.PDF](../../)