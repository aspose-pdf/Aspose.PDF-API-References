---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PngOptions. Representa opções de conversão de Pdf para Png para o plugin Png
type: docs
weight: 9180
url: /pt/net/aspose.pdf.plugins/pngoptions/
---
## Classe PngOptions

Representa opções de conversão de Pdf para Png para o plugin [`Png`](../png/).

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PngOptions](pngoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtém o modo de conversão de imagem. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Retorna a coleção de dados do plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Retorna o nome da operação. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtém ou define o valor de resolução das imagens resultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtém ou define uma lista de páginas para o processo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Adiciona nova fonte de dados à coleção de dados do plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Define nova fonte de dados para salvar. Pode ser apenas um . Se você quiser salvar imagens em fluxos de memória, passe null como parâmetro. |

### Veja Também

* classe [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)