---
title: Class EmfDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.EmfDevice 类。表示图像设备，帮助将 PDF 文档页面保存为 EMF
type: docs
weight: 3580
url: /zh/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

表示图像设备，帮助将 PDF 文档页面保存为 EMF。

```csharp
public sealed class EmfDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | 使用默认的光栅图像分辨率初始化 `EmfDevice` 类的新实例，该图像写入 EMF。 |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | 使用提供的页面大小和默认的光栅图像分辨率（=150）初始化 `EmfDevice` 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | 初始化 `EmfDevice` 类的新实例。写入 EMF 的光栅图像的分辨率，请参见 [`Resolution`](../resolution/) 类。 |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | 使用提供的图像尺寸和默认的光栅图像分辨率（=150）初始化 `EmfDevice` 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | 使用提供的页面大小和写入 EMF 的光栅图像的分辨率初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | 使用提供的图像尺寸和写入 EMF 的光栅图像的分辨率初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 获取图像分辨率。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 获取图像输出宽度。 |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | 将页面转换为 EMF 并将其保存在输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## Examples

以下示例演示如何将 PDF 文件转换为 EMF 图像。

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