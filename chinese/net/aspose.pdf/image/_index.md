---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Image 类。表示图像
type: docs
weight: 5860
url: /zh/net/aspose.pdf/image/
---
## 图像类

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
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | 获取或设置图像缩放。 |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | 获取或设置图像流。 |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | 获取或设置一个布尔值，指示图像在生成过程中是否使用分辨率 |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | 获取或设置一个布尔值，指示图像是否被强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则此属性必须设置为 true。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否将在下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Title](../../aspose.pdf/image/title/) { get; set; } | 获取或设置一个字符串值，指示图像的标题。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | 克隆图像。 |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | 返回图像的 MIME 类型。 |

## 示例

以下示例演示如何将图像（PNG、JPEG、GIF、BMP 或其他图像格式）转换为 PDF 文件。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
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

### 另请参阅

* 类 [BaseParagraph](../baseparagraph/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)