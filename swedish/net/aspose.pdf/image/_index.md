---
title: "Klass Image"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Image klass. Representerar en bild."
type: docs
weight: 5990
url: /sv/net/aspose.pdf/image/
---
## Image class

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
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Hämtar eller anger okomprimerade bildbyte. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Hämtar bildens bitmapstorlek. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Hämtar eller anger bildfilen. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Hämtar eller anger bildfilens typ. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Hämtar eller anger bildens höjd. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Hämtar eller anger bildens bredd. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av stycket. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Hämtar eller anger bildens skala. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Hämtar eller anger bildströmmen. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om bilden använder upplösning under generering. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-underformat används måste denna egenskap sättas till true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Hämtar eller anger ett strängvärde som indikerar bildens titel. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Klona bilden. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Returnerar mime-typ för bilden. |

## Exempel

Följande exempel visar hur man konverterar bilder (PNG, JPEG, GIF, BMP eller andra bildformat) till en PDF-fil.

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Sökvägen till din bild (bmp, png, gif, jpeg osv.) fil.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initiera ett tomt PDF-dokument
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Läs in exempelbildfil
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Spara utdata PDF-dokument
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

### Se även

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


