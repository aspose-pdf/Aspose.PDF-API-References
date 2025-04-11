---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.TiffDevice. Cette classe aide à enregistrer le document pdf page par page dans une seule image tiff
type: docs
weight: 3700
url: /fr/net/aspose.pdf.devices/tiffdevice/
---
## Classe TiffDevice

Cette classe aide à enregistrer le document pdf page par page dans une seule image tiff.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Initialise une nouvelle instance de la classe `TiffDevice` avec des paramètres par défaut. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance de la classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance de la classe `TiffDevice`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Obtient ou définit le mode de présentation des formulaires. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Obtient la résolution de l'image. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Obtient les paramètres pour mapper le pdf dans l'image tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Effectue la binarisation de Bradley pour le flux d'entrée. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Traite l'ensemble du document et enregistre les résultats dans le flux. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Traite l'ensemble du document et enregistre les résultats dans un fichier. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Convertit certaines pages du document en tiff et les enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Traite certaines pages du document et enregistre les résultats dans un fichier. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en images TIFF.

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

### Voir aussi

* classe [DocumentDevice](../documentdevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)