---
title: "类 Image"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Image 类。表示图像。"
type: docs
weight: 5990
url: /zh/net/aspose.pdf/image/
---
## Image class

表示图像。

```csharp
public sealed class Image : BaseParagraph
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Image](image/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | 获取或设置未压缩的图像字节。 |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | 获取图像位图大小。 |
| [File](../../aspose.pdf/image/file/) { get; set; } | 获取或设置图像文件。 |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | 获取或设置图像文件类型。 |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | 获取或设置图像高度。 |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | 获取或设置图像宽度。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 获取或设置段落的水平对齐方式 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | 获取或设置图像比例。 |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | 获取或设置图像流。 |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | 获取或设置一个布尔值，指示在生成过程中图像是否使用分辨率 |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | 获取或设置一个布尔值，指示图像是否被强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 pdf 生成） |
| [Title](../../aspose.pdf/image/title/) { get; set; } | 获取或设置一个字符串值，指示图像的标题。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将位于 ZIndex 较小的图形之上。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本的后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | 克隆图像。 |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | 返回图像的 MIME 类型。 |

## 示例

以下示例展示了如何将图像（PNG、JPEG、GIF、BMP 或其他图像格式）转换为 PDF 文件。

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// 您的图像（bmp、png、gif、jpeg 等）文件的路径。
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//初始化空的 PDF Document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // 加载示例图像文件
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // 保存输出 PDF Document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### 另请参见

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


