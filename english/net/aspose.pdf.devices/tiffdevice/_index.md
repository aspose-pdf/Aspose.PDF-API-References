---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TiffDevice class. This class helps to save pdf document page by page into the one tiff image
type: docs
weight: 3700
url: /net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

This class helps to save pdf document page by page into the one tiff image.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Initializes a new instance of the `TiffDevice` class with default settings. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |

## Properties

| Name | Description |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Gets image output height. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Gets image resolution. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Gets settings for mapping pdf into tiff image. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Do Bradley binarization for input stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Processes the whole document and saves results into stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Processes the whole document and saves results into file. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Converts certain document pages into tiff and save it in the output stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Processes certain pages of the document and saves results into file. |

## Examples

The following example shows how to convert PDF file to TIFF Images.

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

### See Also

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


