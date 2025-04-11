---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TiffDevice-Klasse. Diese Klasse hilft, PDF-Dokumente seitenweise in ein einzelnes TIFF-Bild zu speichern.
type: docs
weight: 3700
url: /de/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice-Klasse

Diese Klasse hilft, PDF-Dokumente seitenweise in ein einzelnes TIFF-Bild zu speichern.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Initialisiert eine neue Instanz der `TiffDevice`-Klasse mit den Standardeinstellungen. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initialisiert eine neue Instanz der `TiffDevice`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Ruft die Höhe der Bildausgabe ab. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Ruft die Einstellungen für die Zuordnung von PDF in ein TIFF-Bild ab. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Ruft die Breite der Bildausgabe ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Führt die Bradley-Binarisierung für den Eingabestream durch. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse im Stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einer Datei. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine bestimmte Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Konvertiert bestimmte Dokumentseiten in TIFF und speichert sie im Ausgabestream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Verarbeitet bestimmte Seiten des Dokuments und speichert die Ergebnisse in einer Datei. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in TIFF-Bilder konvertiert.

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
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
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
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### Siehe auch

* Klasse [DocumentDevice](../documentdevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)