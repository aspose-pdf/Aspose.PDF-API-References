---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.GifDevice-Klasse. Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in GIF zu speichern
type: docs
weight: 3600
url: /de/net/aspose.pdf.devices/gifdevice/
---
## GifDevice-Klasse

Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in GIF zu speichern.

```csharp
public sealed class GifDevice : ImageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Initialisiert eine neue Instanz der `GifDevice`-Klasse mit der Standardauflösung. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Initialisiert eine neue Instanz der `GifDevice`-Klasse mit der angegebenen Seitengröße, Standardauflösung (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Initialisiert eine neue Instanz der `GifDevice`-Klasse. Auflösung für die resultierende Bilddatei, siehe [`Resolution`](../resolution/) Klasse. |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Initialisiert eine neue Instanz der `GifDevice`-Klasse mit den angegebenen Bildabmessungen, Standardauflösung (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Initialisiert eine neue Instanz der `GifDevice`-Klasse mit der angegebenen Seitengröße und Auflösung. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Initialisiert eine neue Instanz der `GifDevice`-Klasse mit den angegebenen Bildabmessungen und Auflösung. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Standardmäßig wird der Wert CropBox verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Bildausgabehöhe ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Bildausgabebreite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Konvertiert die Seite in GIF und speichert sie im Ausgabestrom. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in GIF-Bilder konvertiert.

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

### Siehe auch

* Klasse [ImageDevice](../imagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)