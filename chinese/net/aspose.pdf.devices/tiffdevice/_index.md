---
title: "类 TiffDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.TiffDevice 类。此类帮助将 pdf Document 按 page 保存为单个 tiff 图像"
type: docs
weight: 3820
url: /zh/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

此类帮助将 PDF 文档逐页保存为单个 tiff 图像。

```csharp
public sealed class TiffDevice : DocumentDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | 使用默认设置初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | 初始化 `TiffDevice` 类的新实例。 |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | 初始化 `TiffDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | 获取图像分辨率。 |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | 获取将 pdf 映射到 tiff 图像的设置。 |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | 获取图像输出宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | 对输入流执行 Bradley 二值化。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | 处理整个文档并将结果保存到流中。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | 处理整个文档并将结果保存到文件中。 |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | 将特定文档页面转换为 TIFF 并保存到输出流中。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | 处理文档的特定页面并将结果保存到文件中。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 TIFF 图像。

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
		
		// 创建 TiffSettings 对象。
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// 创建 TIFF 设备。
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// 将 PDF 文档转换为 TIFF 图像。
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

### 另请参见

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


