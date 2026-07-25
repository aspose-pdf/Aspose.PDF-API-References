---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Aspose.PDF for Java API 参考"
description: "com.aspose.pdf.devices 包提供用于将文档表示为图像或纯文本的类。"
type: docs
weight: 140
url: /zh/java/com.aspose.pdf.devices/
---
com.aspose.pdf.devices 包提供用于将文档表示为图像或纯文本的类。

## 类

| 类 | 描述 |
| --- | --- |
| [BmpDevice](./bmpdevice/) | 表示帮助将 PDF 文档页面保存为 bmp 的图像设备。 |
| [Device](./device/) | 所有类型设备的抽象类。Device 用于以某种格式表示 pdf 文档。例如，文档页面可以表示为图像或文本。 |
| [DicomDevice](./dicomdevice/) | 表示帮助将 PDF 文档页面保存为 Dicom 格式的图像设备。 |
| [DocumentDevice](./documentdevice/) | 用于处理整个 pdf 文档的所有设备的抽象类。 |
| [EmfDevice](./emfdevice/) | 表示帮助将 PDF 文档页面保存为 emf 的图像设备。 |
| [FormPresentationMode](./formpresentationmode/) | 用于在打印或将 pdf 文档转换为图像时指定表单呈现模式。 |
| [GifDevice](./gifdevice/) | 表示帮助将 PDF 文档页面保存为 gif 的图像设备。 |
| [GraphicsDevice](./graphicsdevice/) | 表示帮助将 PDF 文档页面渲染为图形的图像设备。 |
| [ImageDevice](./imagedevice/) | 图像设备的抽象类。 |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | 表示帮助将 PDF 文档页面保存为 jpeg 的图像设备。 |
| [Margins](./margins/) | 此类表示图像的边距。 |
| [PageDevice](./pagedevice/) | 用于处理 pdf 文档特定页面的所有设备的抽象类。 |
| [PngDevice](./pngdevice/) | 表示帮助将 PDF 文档页面保存为 png 的图像设备。 |
| [Resolution](./resolution/) | 表示用于保存图像分辨率的类。 |
| [TextDevice](./textdevice/) | <p> 表示用于将 pdf 文档页面转换为文本的类。 </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> {@code TextDevice} 对象主要用于从 pdf 页面提取文本。 </p> |
| [ThumbnailDevice](./thumbnaildevice/) | 表示将 pdf 文档页面保存为缩略图的图像设备。 |
| [TiffDevice](./tiffdevice/) | 此类帮助将 pdf 文档逐页保存为单个 tiff 图像。 |
| [TiffSettings](./tiffsettings/) | 此类表示将 pdf 导入为 Tiff 的设置。 |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | 类表示索引转换类型。 |
## Enums

| 枚举 | 描述 |
| --- | --- |
| [ColorDepth](./colordepth/) | 用于指定传递给 Tiff 图像设备的参数值。 |
| [CompressionType](./compressiontype/) | 用于指定传递给 Tiff 图像设备的参数值。 |
| [ShapeType](./shapetype/) | 此枚举表示提取图像的形状类型。 |
