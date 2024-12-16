---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.PngDevice class. Represents image device that helps to save pdf document pages into png
type: docs
weight: 3630
url: /net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

Represents image device that helps to save pdf document pages into png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Initializes a new instance of the `PngDevice` class with default resolution. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Initializes a new instance of the `PngDevice` class with provided page size, default resolution (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Initializes a new instance of the `PngDevice` class.  Resolution for the result image file, see [`Resolution`](../resolution/) class. |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Initializes a new instance of the `PngDevice` class with provided image dimensions, default resolution (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Initializes a new instance of the `PngDevice` class with provided page size and resolution. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the `PngDevice` class with provided image dimensions and resolution. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Gets or sets if image has transparent background. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Converts the page into png and saves it in the output stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

## Examples

The following example shows how to convert PDF file to PNG Images.

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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


