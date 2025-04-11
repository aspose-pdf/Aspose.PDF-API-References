---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfToImageOptions. Representa opções para o plugin PdfToImage
type: docs
weight: 9130
url: /pt/net/aspose.pdf.plugins/pdftoimageoptions/
---
## Classe PdfToImageOptions

Representa opções para o [`PdfToImage`](../pdftoimage/) plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtém o modo de conversão de imagem. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Retorna a coleção de dados do plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Retorna o nome da operação. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtém ou define o valor de resolução das imagens resultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtém ou define uma lista de páginas para o processo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Adiciona nova fonte de dados à coleção de dados do plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Define nova fonte de dados para salvar. Pode ser apenas um. Se você quiser salvar imagens em fluxos de memória, passe null como parâmetro. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Define diferentes modos que podem ser usados ao converter de documento PDF para imagem Jpeg. Veja a classe [`JpegOptions`](../jpegoptions/). |

## Observações

A classe PdfImageOptions contém funções básicas para adicionar dados (arquivos, fluxos) representando documentos PDF de entrada.

### Veja Também

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)