---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TiffOptions. Representa opções de conversão de Pdf para Tiff para o plugin Tiff
type: docs
weight: 9420
url: /pt/net/aspose.pdf.plugins/tiffoptions/
---
## Classe TiffOptions

Representa opções de conversão de Pdf para Tiff para o plugin [`Tiff`](../tiff/).

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TiffOptions](tiffoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Obtém ou define um valor limite da transformação de cores em preto e branco. Este parâmetro pode ser aplicado com EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Obtém ou define o tipo de compressão. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtém o modo de conversão de imagem. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Obtém ou define a profundidade de cor. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Retorna a coleção de dados do plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Retorna o nome da operação. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtém ou define o valor de resolução das imagens resultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtém ou define uma lista de páginas para o processo. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Obtém e define uma flag que permite salvar todas as páginas em um tiff multipágina. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Obtém ou define o tipo de forma. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Obtém ou define um valor que indica se deve pular páginas em branco. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Adiciona uma nova fonte de dados à coleção de dados do plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Define uma nova fonte de dados para salvar. Pode ser apenas um . Se você quiser salvar imagens em fluxos de memória, passe null como parâmetro. |

### Veja Também

* classe [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)