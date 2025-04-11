---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Image. Representa imagem
type: docs
weight: 5860
url: /pt/net/aspose.pdf/image/
---
## Classe Imagem

Representa imagem.

```csharp
public sealed class Image : BaseParagraph
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Image](image/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Obtém ou define bytes de imagem não compactados. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | Obtém o tamanho do bitmap da imagem. |
| [File](../../aspose.pdf/image/file/) { get; set; } | Obtém ou define o arquivo da imagem. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | Obtém ou define o tipo de arquivo da imagem. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | Obtém ou define a altura da imagem. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | Obtém ou define a largura da imagem. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | Obtém ou define a escala da imagem. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | Obtém ou define o fluxo da imagem. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Obtém ou define um valor bool que indica se a imagem usa resolução durante a geração |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | Obtém ou define um valor bool que indica se a imagem é forçada a ser preto e branco. Se uma imagem TIFF do subformato CCITT for usada, esta propriedade deve ser definida como verdadeira. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | Obtém ou define um valor de string que indica o título da imagem. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | Clona a imagem. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | Retorna o tipo mime para a imagem. |

## Exemplos

O exemplo a seguir mostra como converter imagens (PNG, JPEG, GIF, BMP ou outros formatos de imagem) em um arquivo PDF.

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

### Veja Também

* classe [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)