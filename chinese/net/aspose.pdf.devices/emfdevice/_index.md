---
title: "类 EmfDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.EmfDevice 类。表示帮助将 pdf 文档页面保存为 emf 的图像设备。"
type: docs
weight: 3700
url: /zh/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

表示帮助将 PDF 文档页面保存为 emf 的图像设备。

```csharp
public sealed class EmfDevice : ImageDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | 使用写入 emf 的栅格图像的默认分辨率初始化 `EmfDevice` 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | 使用提供的页面尺寸以及写入 emf 的栅格图像的默认分辨率（=150）初始化 `EmfDevice` 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | 初始化 `EmfDevice` 类的新实例。写入 emf 的栅格图像的分辨率，请参阅 [`Resolution`](../resolution/) 类。 |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | 使用提供的图像尺寸以及写入 emf 的栅格图像的默认分辨率（=150）初始化 `EmfDevice` 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | 使用提供的页面尺寸以及写入 emf 的栅格图像的分辨率初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | 使用提供的图像尺寸以及写入 emf 的栅格图像的分辨率初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | 将页面转换为 emf 并保存到输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 EMF 图像。

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

		// 初始化 EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// 转换特定页面并将图像保存到流中
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// 关闭流
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

### 另请参见

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


