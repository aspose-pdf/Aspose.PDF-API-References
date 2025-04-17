---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfConverter. Representa uma classe para converter cada página de arquivos pdf em imagens suportando BMP, JPEG, PNG e TIFF agora. Conteúdo suportado em pdfs imagens, formulário, comentário.
type: docs
weight: 4440
url: /pt/net/aspose.pdf.facades/pdfconverter/
---
## Classe PdfConverter

Representa uma classe para converter cada página de um arquivo pdf em imagens, suportando BMP, JPEG, PNG e TIFF agora. Conteúdo suportado em pdfs: imagens, formulário, comentário.

```csharp
public sealed class PdfConverter : Facade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Inicializa um novo objeto `PdfConverter`. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Inicializa um novo objeto `PdfConverter` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Obtém ou define a posição final que você deseja converter. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação do formulário. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Obtém a contagem de páginas. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Obtém ou define a OwnerPassword do documento. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Obtém ou define as opções de renderização. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Obtém ou define a resolução durante a conversão. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Obtém ou define a posição inicial que você deseja converter. O valor mínimo é 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Obtém ou define a UserPassword do documento. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Vincula um fluxo Pdf para conversão. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Vincula um arquivo Pdf para conversão. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Fecha a instância de PdfConverter e libera os recursos. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Realiza alguns trabalhos iniciais para converter um documento pdf em imagens. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Salva a imagem no fluxo com o formato de imagem padrão - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Salva a imagem em um arquivo com o formato de imagem padrão - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Salva a imagem no fluxo com o formato de imagem fornecido. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Salva a imagem no fluxo com o tamanho de página fornecido. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Salva a imagem em um arquivo com o formato de imagem fornecido. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Salva a imagem em um arquivo com o tamanho de página fornecido e formato de imagem padrão - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Salva a imagem no fluxo com o formato de imagem e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Salva a imagem no fluxo com o tamanho de página fornecido. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Salva a imagem em um arquivo com o formato de imagem e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Salva a imagem em um arquivo com o tamanho de página e formato de imagem fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Salva a imagem no fluxo com o formato de imagem, tamanho e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Salva a imagem no fluxo com o tamanho de página, formato de imagem e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Salva a imagem em um arquivo com o formato de imagem e dimensões fornecidas. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Salva a imagem em um arquivo com o tamanho de página, formato de imagem e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Salva a imagem no fluxo com o formato de imagem, tamanho e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Salva a imagem no fluxo com o formato de imagem, dimensões e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Salva a imagem em um arquivo com o formato de imagem, tamanho da imagem e qualidade fornecidos. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Salva a imagem em um arquivo com o formato de imagem, dimensões e qualidade fornecidas. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Indica se o arquivo pdf tem mais imagens ou não. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Converte cada página de um documento pdf em imagens e salva as imagens em um único fluxo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Mescla uma lista de fluxos de imagem em um único fluxo de imagem. Formatos de saída png/jpg/tiff são suportados, caso utilize um formato de saída não suportado, o fluxo de saída é codificado como Jpeg por padrão. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Mescla uma lista de fluxos tiff em um único fluxo tiff de múltiplos quadros. |

### Veja Também

* classe [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)