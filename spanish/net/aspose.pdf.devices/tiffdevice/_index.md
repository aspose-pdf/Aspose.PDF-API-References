---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.TiffDevice. Esta clase ayuda a guardar el documento pdf página por página en una sola imagen tiff
type: docs
weight: 3700
url: /es/net/aspose.pdf.devices/tiffdevice/
---
## Clase TiffDevice

Esta clase ayuda a guardar el documento pdf página por página en una sola imagen tiff.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Inicializa una nueva instancia de la clase `TiffDevice` con configuraciones predeterminadas. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Inicializa una nueva instancia de la clase `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Inicializa una nueva instancia de la clase `TiffDevice`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Obtiene la altura de salida de la imagen. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Obtiene la resolución de la imagen. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Obtiene la configuración para mapear pdf en la imagen tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Obtiene el ancho de salida de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Realiza la binarización de Bradley para el flujo de entrada. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Procesa todo el documento y guarda los resultados en el flujo. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Procesa todo el documento y guarda los resultados en el archivo. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Convierte ciertas páginas del documento en tiff y las guarda en el flujo de salida. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Procesa ciertas páginas del documento y guarda los resultados en el archivo. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a imágenes TIFF.

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

### Ver También

* clase [DocumentDevice](../documentdevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)