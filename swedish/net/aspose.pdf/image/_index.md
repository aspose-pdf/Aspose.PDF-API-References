---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Image klass. Representerar bild
type: docs
weight: 5860
url: /sv/net/aspose.pdf/image/
---
## Bild klass

Representerar bild.

```csharp
public sealed class Image : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Image](image/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Hämtar eller ställer in okomprimerade bildbytes. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Hämtar bildens bitmapstorlek. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Hämtar eller ställer in bildfilen. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Hämtar eller ställer in bildfiltypen. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Hämtar eller ställer in bildens höjd. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Hämtar eller ställer in bildens bredd. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av stycket |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Hämtar eller ställer in bildskalan. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Hämtar eller ställer in bildströmmen. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Hämtar eller ställer in ett bool-värde som anger om bilden använder upplösning under generering |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Hämtar eller ställer in ett bool-värde som anger om bilden tvingas att vara svartvit. Om TIFF-bild av CCITT-underformat används, måste denna egenskap ställas in på true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som anger om detta stycke kommer att vara i nästa kolumn. Standard är false. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in ett stycke som är inline. Standard är false. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är false. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som anger om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är false. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Hämtar eller ställer in ett strängvärde som anger titeln på bilden. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Klona bilden. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Returnerar mime-typ för bilden. |

## Exempel

Följande exempel visar hur man konverterar bilder (PNG, JPEG, GIF, BMP eller andra bildformat) till en PDF-fil.

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

### Se Även

* klass [BaseParagraph](../baseparagraph/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)