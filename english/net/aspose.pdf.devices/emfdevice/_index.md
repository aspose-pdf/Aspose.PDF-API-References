---
title: Class EmfDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.EmfDevice class. Represents image device that helps to save pdf document pages into emf
type: docs
weight: 2080
url: /net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

Represents image device that helps to save pdf document pages into emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Initializes a new instance of the `EmfDevice` class with default resolution of raster image written to emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Initializes a new instance of the `EmfDevice` class with provided page size, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Initializes a new instance of the `EmfDevice` class.  Resolution for the raster image written to emf, see [`Resolution`](../resolution/) class. |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Initializes a new instance of the `EmfDevice` class with provided image dimensions, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Initializes a new instance of the [`JpegDevice`](../jpegdevice/) class with provided page size, and resolution for the raster image written to emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the [`JpegDevice`](../jpegdevice/) class with provided image dimensions, and resolution for the raster image written to emf. |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Converts the page into emf and saves it in the output stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

## Examples

The following example shows how to convert PDF file to EMF Images.

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

		// Initialize EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Close stream
				emfStream.Close();
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
	
		' Initialize EmfDevice   
		Dim emfDevice As EmfDevice = New EmfDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using emfStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.emf", FileMode.Create)
			
				' Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages(pageCount), emfStream)

				' Close stream
				emfStream.Close()
			End Using
		Next
	End Using
```

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


