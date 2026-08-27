---
title: "Klass PngDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.PngDevice-klass. Representerar en bildenhet som hjälper till att spara pdf-dokumentets sidor som png"
type: docs
weight: 3770
url: /sv/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

Representerar bildenhet som hjälper till att spara PDF-dokumentets sidor som PNG.

```csharp
public sealed class PngDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Initierar en ny instans av klassen `PngDevice` med standardupplösning. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Initierar en ny instans av klassen `PngDevice` med angiven sidstorlek, standardupplösning (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Initierar en ny instans av klassen `PngDevice`.  Upplösning för den resulterande bildfilen, se klassen [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Initierar en ny instans av klassen `PngDevice` med angivna bilddimensioner, standardupplösning (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av klassen `PngDevice` med angiven sidstorlek och upplösning. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av klassen `PngDevice` med angivna bilddimensioner och upplösning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Hämtar eller anger formulärets presentationsläge. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Hämtar bildens utdatahöjd. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Hämtar eller anger renderingsalternativ. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Hämtar bildens upplösning. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Hämtar eller anger om bilden har transparent bakgrund. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Hämtar bildens utdata bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Konverterar sidan till Bitmap. |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Konverterar sidan till png och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF‑fil till PNG‑bilder.

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

		// Initiera PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Konvertera en specifik sida och spara bilden till strömmen
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Stäng strömmen
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

### Se även

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


