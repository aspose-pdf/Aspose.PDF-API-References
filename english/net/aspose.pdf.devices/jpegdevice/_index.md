---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.JpegDevice class. Represents image device that helps to save pdf document pages into jpeg
type: docs
weight: 3730
url: /net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

Represents image device that helps to save pdf document pages into jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Initializes a new instance of the `JpegDevice` class with default resolution and maximum quality. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Initializes a new instance of the `JpegDevice` class. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Initializes a new instance of the `JpegDevice` class with provided page size, default resolution (=150) and maximum quality. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Initializes a new instance of the `JpegDevice` class.  Resolution for the result image file, see [`Resolution`](../resolution/) class. |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Initializes a new instance of the `JpegDevice` class with provided image dimensions, default resolution (=150) and maximum quality. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Initializes a new instance of the `JpegDevice` class with provided page size, resolution and maximum quality. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Initializes a new instance of the `JpegDevice` class. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Initializes a new instance of the `JpegDevice` class with provided image dimensions, resolution and maximum quality. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Initializes a new instance of the `JpegDevice` class with provided page size, resolution and quality. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Initializes a new instance of the `JpegDevice` class with provided image dimensions, resolution and quality. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Converts the page into jpeg and saves it in the output stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

## Examples

The following example shows how to convert PDF file to JPEG Images.

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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


