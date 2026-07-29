---
title: "类 PngDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.PngDevice 类。表示帮助将 pdf 文档页面保存为 png 的图像设备。"
type: docs
weight: 3770
url: /zh/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

表示帮助将 PDF 文档页面保存为 png 的图像设备。

```csharp
public sealed class PngDevice : ImageDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | 使用默认分辨率初始化 `PngDevice` 类的新实例。 |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | 使用提供的页面尺寸和默认分辨率（=150）初始化 `PngDevice` 类的新实例。 |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | 初始化 `PngDevice` 类的新实例。结果图像文件的分辨率，请参阅 [`Resolution`](../resolution/) 类。 |
| [PngDevice](pngdevice/#constructor_4)(int, int) | 使用提供的图像尺寸初始化 `PngDevice` 类的新实例，默认分辨率 (=150)。 |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | 使用提供的页面尺寸和分辨率初始化 `PngDevice` 类的新实例。 |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | 使用提供的图像尺寸和分辨率初始化 `PngDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 获取图像分辨率。 |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | 获取或设置图像是否具有透明背景。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 获取图像输出宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | 将页面转换为位图。 |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | 将页面转换为 png 并保存到输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 PNG 图像。

```csharp
[C#]
	// 您的 PDF 目录路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// PDF 文件的文件名。
	string pdfFile = @"YOUR_PDF_FILE";

	// 初始化 Document 类的实例。
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// 创建 Resolution 对象 \t
		Resolution resolution = new Resolution(300);

		// 初始化 PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// 转换特定页面并将图像保存到流中
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// 关闭流
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

### 另请参见

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


