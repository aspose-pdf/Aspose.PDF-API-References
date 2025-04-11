---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.PngDevice-Klasse. Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in PNG zu speichern
type: docs
weight: 3650
url: /de/net/aspose.pdf.devices/pngdevice/
---
## PngDevice-Klasse

Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in PNG zu speichern.

```csharp
public sealed class PngDevice : ImageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Initialisiert eine neue Instanz der `PngDevice`-Klasse mit der Standardauflösung. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Initialisiert eine neue Instanz der `PngDevice`-Klasse mit der angegebenen Seitengröße, Standardauflösung (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Initialisiert eine neue Instanz der `PngDevice`-Klasse. Auflösung für die resultierende Bilddatei, siehe [`Resolution`](../resolution/) Klasse. |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Initialisiert eine neue Instanz der `PngDevice`-Klasse mit den angegebenen Bildabmessungen, Standardauflösung (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Initialisiert eine neue Instanz der `PngDevice`-Klasse mit der angegebenen Seitengröße und Auflösung. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Initialisiert eine neue Instanz der `PngDevice`-Klasse mit den angegebenen Bildabmessungen und Auflösung. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Höhe des Bildausgangs ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Ruft ab oder legt fest, ob das Bild einen transparenten Hintergrund hat. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Breite des Bildausgangs ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Konvertiert die Seite in PNG und speichert sie im Ausgabestrom. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in PNG-Bilder konvertiert.

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

### Siehe auch

* Klasse [ImageDevice](../imagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)