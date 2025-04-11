---
title: Class EmfDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.EmfDevice klass. Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i emf
type: docs
weight: 3580
url: /sv/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice klass

Representerar en bildenhet som hjälper till att spara pdf-dokument sidor i emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Initierar en ny instans av `EmfDevice` klassen med standardupplösning för rasterbild som skrivs till emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Initierar en ny instans av `EmfDevice` klassen med angiven sidstorlek och standardupplösning för rasterbild som skrivs till emf (=150) |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Initierar en ny instans av `EmfDevice` klassen. Upplösning för rasterbild som skrivs till emf, se [`Resolution`](../resolution/) klass. |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Initierar en ny instans av `EmfDevice` klassen med angivna bilddimensioner och standardupplösning för rasterbild som skrivs till emf (=150) |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angiven sidstorlek och upplösning för rasterbild som skrivs till emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Initierar en ny instans av [`JpegDevice`](../jpegdevice/) klassen med angivna bilddimensioner och upplösning för rasterbild som skrivs till emf. |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Konverterar sidan till emf och sparar den i utdataflödet. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till EMF-bilder.

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

		// Initialize EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Close stream
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

### Se Även

* klass [ImageDevice](../imagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* sammansättning [Aspose.PDF](../../)