---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Image. Representa una imagen
type: docs
weight: 5860
url: /es/net/aspose.pdf/image/
---
## Clase Imagen

Representa una imagen.

```csharp
public sealed class Image : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Image](image/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Obtiene o establece los bytes de imagen sin comprimir. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Obtiene el tamaño del bitmap de la imagen. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Obtiene o establece el archivo de imagen. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Obtiene o establece el tipo de archivo de imagen. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Obtiene o establece la altura de la imagen. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Obtiene o establece el ancho de la imagen. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del párrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Obtiene o establece la escala de la imagen. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Obtiene o establece el flujo de la imagen. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Obtiene o establece un valor booleano que indica si la imagen utiliza resolución durante la generación. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Obtiene o establece un valor booleano que indica si la imagen está forzada a ser en blanco y negro. Si se utiliza una imagen TIFF de subformato CCITT, esta propiedad debe establecerse en verdadero. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Obtiene o establece un valor de cadena que indica el título de la imagen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Clona la imagen. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Devuelve el tipo MIME para la imagen. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir imágenes (PNG, JPEG, GIF, BMP u otros formatos de imagen) a un archivo PDF.

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

### Ver También

* clase [BaseParagraph](../baseparagraph/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)