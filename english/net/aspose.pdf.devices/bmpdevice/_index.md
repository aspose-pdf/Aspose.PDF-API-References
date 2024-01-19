---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.BmpDevice class. Represents image device that helps to save pdf document pages into bmp
type: docs
weight: 1670
url: /net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

Represents image device that helps to save pdf document pages into bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Initializes a new instance of the `BmpDevice` class with default resolution. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Initializes a new instance of the `BmpDevice` class with provided page size, default resolution (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Initializes a new instance of the `BmpDevice` class.  Resolution for the result image file, see [`Resolution`](../resolution/) class. |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Initializes a new instance of the `BmpDevice` class with provided image dimensions, default resolution (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Initializes a new instance of the `BmpDevice` class with provided page size and resolution. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the `BmpDevice` class with provided image dimensions and resolution. |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Converts the page into bmp and saves it in the output stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

## Examples

The following example shows how to convert PDF file to BMP Images.

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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


