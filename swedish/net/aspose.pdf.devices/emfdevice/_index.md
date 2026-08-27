---
title: "Klass EmfDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.EmfDevice class. Representerar bildenhet som hjälper till att spara pdf-dokumentets sidor i emf"
type: docs
weight: 3700
url: /sv/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

Representerar en bildenhet som hjälper till att spara pdf‑dokumentets sidor som emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Initierar en ny instans av `EmfDevice`-klassen med standardupplösning för rasterbild som skrivs till emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Initierar en ny instans av `EmfDevice`-klassen med angiven sidstorlek och standardupplösning för rasterbild som skrivs till emf (=150). |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Initierar en ny instans av `EmfDevice`-klassen. Upplösning för rasterbild som skrivs till emf, se [`Resolution`](../resolution/) klass. |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Initierar en ny instans av `EmfDevice`-klassen med angivna bilddimensioner och standardupplösning för rasterbild som skrivs till emf (=150). |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angiven sidstorlek och upplösning för rasterbild som skrivs till emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angivna bilddimensioner och upplösning för rasterbild som skrivs till emf. |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Konverterar sidan till emf och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till EMF-bilder.

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

		// Initiera EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Konvertera en specifik sida och spara bilden till strömmen
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Stäng strömmen
				emfStream.Close();
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
	
		' Initialize EmfDevice   
		Dim emfDevice As EmfDevice = New EmfDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using emfStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.emf", FileMode.Create)
			
				' Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages(pageCount), emfStream)

				' Close stream
				emfStream.Close()
			End Using
		Next
	End Using
```

### Se även

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


