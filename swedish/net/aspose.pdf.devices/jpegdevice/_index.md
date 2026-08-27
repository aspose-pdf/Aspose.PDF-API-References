---
title: "Klass JpegDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.JpegDevice-klass. Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som jpeg"
type: docs
weight: 3740
url: /sv/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

Representerar en bildenhet som hjälper till att spara pdf‑dokumentets sidor som jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Initierar en ny instans av klassen `JpegDevice` med standardupplösning och maximal kvalitet. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Initierar en ny instans av klassen `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Initierar en ny instans av klassen `JpegDevice` med angiven sidstorlek, standardupplösning (=150) och maximal kvalitet. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Initierar en ny instans av klassen `JpegDevice`.  Upplösning för den resulterande bildfilen, se [`Resolution`](../resolution/) klass. |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Initierar en ny instans av klassen `JpegDevice` med angivna bilddimensioner, standardupplösning (=150) och maximal kvalitet. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Initierar en ny instans av klassen `JpegDevice` med angiven sidstorlek, upplösning och maximal kvalitet. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Initierar en ny instans av klassen `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Initierar en ny instans av klassen `JpegDevice` med angivna bilddimensioner, upplösning och maximal kvalitet. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Initierar en ny instans av klassen `JpegDevice` med angiven sidstorlek, upplösning och kvalitet. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Initierar en ny instans av klassen `JpegDevice` med angivna bilddimensioner, upplösning och kvalitet. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller anger formulärets presentationsläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller anger renderingsalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Konverterar sidan till Bitmap. |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Konverterar sidan till jpeg och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till JPEG-bilder.

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

		// Initiera JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Konvertera en specifik sida och spara bilden till strömmen
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Stäng strömmen
				jpegStream.Close();
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
		
		' Initialize JpegDevice
		Dim jpegDevice As JpegDevice = New JpegDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using jpegStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.jpeg", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages(pageCount), jpegStream)

				' Close stream
				jpegStream.Close()
			End Using
		Next
    End Using
```

### Se även

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


