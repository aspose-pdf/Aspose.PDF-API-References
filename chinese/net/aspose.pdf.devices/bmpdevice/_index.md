---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.BmpDevice 类。表示图像设备，帮助将 PDF 文档页面保存为 BMP
type: docs
weight: 3520
url: /zh/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

表示图像设备，帮助将 PDF 文档页面保存为 BMP。

```csharp
public sealed class BmpDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | 使用默认分辨率初始化 `BmpDevice` 类的新实例。 |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | 使用提供的页面大小初始化 `BmpDevice` 类的新实例，默认分辨率 (=150)。 |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | 初始化 `BmpDevice` 类的新实例。结果图像文件的分辨率，请参见 [`Resolution`](../resolution/) 类。 |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | 使用提供的图像尺寸初始化 `BmpDevice` 类的新实例，默认分辨率 (=150)。 |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | 使用提供的页面大小和分辨率初始化 `BmpDevice` 类的新实例。 |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | 使用提供的图像尺寸和分辨率初始化 `BmpDevice` 类的新实例。 |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | 将页面转换为 BMP 并将其保存在输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## Examples

以下示例演示如何将 PDF 文件转换为 BMP 图像。

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