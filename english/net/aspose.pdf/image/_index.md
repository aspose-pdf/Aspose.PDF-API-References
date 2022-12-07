---
title: Image
second_title: Aspose.PDF for .NET API Reference
description: Represents image.
type: docs
weight: 3730
url: /net/aspose.pdf/image/
---
## Image class

Represents image.

```csharp
public sealed class Image : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [Image](image)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [File](../../aspose.pdf/image/file) { get; set; } | Gets or sets the image file. |
| [FileType](../../aspose.pdf/image/filetype) { get; set; } | Gets or sets the image file type. |
| [FixHeight](../../aspose.pdf/image/fixheight) { get; set; } | Gets or sets the image height. |
| [FixWidth](../../aspose.pdf/image/fixwidth) { get; set; } | Gets or sets the image width. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Gets or sets a horizontal alignment of paragraph |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [ImageScale](../../aspose.pdf/image/imagescale) { get; set; } | Gets or sets the image scale. |
| [ImageStream](../../aspose.pdf/image/imagestream) { get; set; } | Gets or sets the image stream. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution) { get; set; } | Gets or sets a bool value that indicates whether the image use resolution during generation |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite) { get; set; } | Gets or sets a bool value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Title](../../aspose.pdf/image/title) { get; set; } | Gets or sets a string value that indicates the title of the image. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Gets or sets a vertical alignment of paragraph |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone)() | Clone the image. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype)(Image) | Returns mime type for image. |

## Examples

The following example shows how to convert images (PNG, JPEG, GIF, BMP, or other image formats) to a PDF file.

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

### See Also

* class [BaseParagraph](../baseparagraph)
* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
