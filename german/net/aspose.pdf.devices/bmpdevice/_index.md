---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.BmpDevice-Klasse. Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in BMP zu speichern.
type: docs
weight: 3520
url: /de/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice-Klasse

Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in BMP zu speichern.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Initialisiert eine neue Instanz der `BmpDevice`-Klasse mit der Standardauflösung. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Initialisiert eine neue Instanz der `BmpDevice`-Klasse mit der angegebenen Seitengröße, Standardauflösung (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Initialisiert eine neue Instanz der `BmpDevice`-Klasse. Auflösung für die resultierende Bilddatei, siehe [`Resolution`](../resolution/) Klasse. |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Initialisiert eine neue Instanz der `BmpDevice`-Klasse mit den angegebenen Bilddimensionen, Standardauflösung (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Initialisiert eine neue Instanz der `BmpDevice`-Klasse mit der angegebenen Seitengröße und Auflösung. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Initialisiert eine neue Instanz der `BmpDevice`-Klasse mit den angegebenen Bilddimensionen und Auflösung. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitenkoordinatentyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Höhe des Bildausgangs ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Breite des Bildausgangs ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Konvertiert die Seite in BMP und speichert sie im Ausgabestream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in BMP-Bilder konvertiert.

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);

		// initialize BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Close stream
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

### Siehe auch

* Klasse [ImageDevice](../imagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)