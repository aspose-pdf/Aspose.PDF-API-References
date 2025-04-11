---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.JpegDevice-Klasse. Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in JPEG zu speichern
type: docs
weight: 3620
url: /de/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice-Klasse

Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in JPEG zu speichern.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit standardmäßiger Auflösung und maximaler Qualität. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit der angegebenen Seitengröße, standardmäßiger Auflösung (=150) und maximaler Qualität. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse. Auflösung für die resultierende Bilddatei, siehe [`Resolution`](../resolution/) Klasse. |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit den angegebenen Bildabmessungen, standardmäßiger Auflösung (=150) und maximaler Qualität. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit der angegebenen Seitengröße, Auflösung und maximaler Qualität. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit den angegebenen Bildabmessungen, Auflösung und maximaler Qualität. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit der angegebenen Seitengröße, Auflösung und Qualität. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Initialisiert eine neue Instanz der `JpegDevice`-Klasse mit den angegebenen Bildabmessungen, Auflösung und Qualität. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Höhe des Bildausgangs ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Breite des Bildausgangs ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Konvertiert die Seite in JPEG und speichert sie im Ausgabestrom. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in JPEG-Bilder konvertiert.

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

		// Initialize JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Close stream
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

### Siehe auch

* Klasse [ImageDevice](../imagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)