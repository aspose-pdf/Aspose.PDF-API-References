---
title: "类 JpegDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.JpegDevice 类。表示帮助将 PDF 文档页面保存为 jpeg 的图像设备。"
type: docs
weight: 3740
url: /zh/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

表示帮助将 PDF 文档页面保存为 jpeg 的图像设备。

```csharp
public sealed class JpegDevice : ImageDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | 使用默认分辨率和最高质量初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_6)(int) | 初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | 使用提供的页面大小、默认分辨率 (=150) 和最高质量初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | 初始化 `JpegDevice` 类的新实例。结果图像文件的分辨率，请参阅 [`Resolution`](../resolution/) 类。 |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | 使用提供的图像尺寸、默认分辨率 (=150) 和最高质量初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | 使用提供的页面大小、分辨率和最高质量初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | 初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | 使用提供的图像尺寸、分辨率和最高质量初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | 使用提供的页面大小、分辨率和质量初始化 `JpegDevice` 类的新实例。 |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | 使用提供的图像尺寸、分辨率和质量初始化 `JpegDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 获取图像分辨率。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 获取图像输出宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | 将页面转换为位图。 |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | 将页面转换为 jpeg 并保存到输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 JPEG 图像。

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

		// 初始化 JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// 转换特定页面并将图像保存到流中
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// 关闭流
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

### 另请参见

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


