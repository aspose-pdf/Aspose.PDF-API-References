---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Image-Klasse. Stellt ein Bild dar
type: docs
weight: 5860
url: /de/net/aspose.pdf/image/
---
## Bildklasse

Stellt ein Bild dar.

```csharp
public sealed class Image : BaseParagraph
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Image](image/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Ruft die unkomprimierten Bildbytes ab oder legt sie fest. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Ruft die Bitmap-Größe des Bildes ab. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Ruft die Bilddatei ab oder legt sie fest. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Ruft den Dateityp des Bildes ab oder legt ihn fest. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Ruft die Höhe des Bildes ab oder legt sie fest. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Ruft die Breite des Bildes ab oder legt sie fest. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft eine horizontale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für den PDF-Generator) ab oder legt ihn fest. |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Ruft den Maßstab des Bildes ab oder legt ihn fest. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Ruft den Bildstrom ab oder legt ihn fest. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Bild bei der Generierung die Auflösung verwendet. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Bild gezwungen ist, schwarz-weiß zu sein. Wenn ein TIFF-Bild des CCITT-Subformats verwendet wird, muss diese Eigenschaft auf true gesetzt werden. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für die PDF-Generierung) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Ruft einen String-Wert ab oder legt ihn fest, der den Titel des Bildes angibt. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Klont das Bild. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Gibt den MIME-Typ für das Bild zurück. |

## Beispiele

Das folgende Beispiel zeigt, wie man Bilder (PNG, JPEG, GIF, BMP oder andere Bildformate) in eine PDF-Datei konvertiert.

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

### Siehe auch

* Klasse [BaseParagraph](../baseparagraph/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)