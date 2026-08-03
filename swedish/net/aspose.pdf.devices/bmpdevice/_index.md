---
title: "Klass BmpDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.BmpDevice-klass. Representerar en bildenhet som hjälper till att spara pdf-dokumentets sidor som bmp"
type: docs
weight: 3640
url: /sv/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

Representerar en bildenhet som hjälper till att spara pdf‑dokumentets sidor som bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Initierar en ny instans av klassen `BmpDevice` med standardupplösning. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Initierar en ny instans av klassen `BmpDevice` med angiven sidstorlek, standardupplösning (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Initierar en ny instans av klassen `BmpDevice`.  Upplösning för den resulterande bildfilen, se klassen [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Initierar en ny instans av klassen `BmpDevice` med angivna bilddimensioner, standardupplösning (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av klassen `BmpDevice` med angiven sidstorlek och upplösning. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av klassen `BmpDevice` med angivna bilddimensioner och upplösning. |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Konverterar sidan till bmp och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till BMP-bilder.

```csharp
[C#]
	// Sökvägen till din PDF-katalog
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Filnamnet på PDF-filen
	string pdfFile = @"YOUR_PDF_FILE";

	// initiera en instans av Document-klassen
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Skapa Resolution-objekt \t
		Resolution resolution = new Resolution(300);

		// initiera BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Konvertera en specifik sida och spara bilden till strömmen
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Stäng strömmen
				bmpStream.Close();
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
		
		' Initialize BmpDevice  
		Dim bmpDevice As BmpDevice = New BmpDevice(resolution)
		
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using bmpStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.bmp", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages(pageCount), bmpStream)

				' Close stream
				bmpStream.Close()
			End Using
		Next
	End Using
```

### Se även

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


