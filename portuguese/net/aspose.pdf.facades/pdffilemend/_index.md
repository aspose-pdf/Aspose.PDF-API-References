---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileMend. Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente
type: docs
weight: 4530
url: /pt/net/aspose.pdf.facades/pdffilemend/
---
## Classe PdfFileMend

Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Construtor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Inicializa um novo objeto `PdfFileMend` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Define um valor bool que indica a quebra de linha nos métodos AddText. Se o valor for verdadeiro, o texto em FormattedText será quebrado. Por padrão, o valor é falso. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Define ou obtém a estratégia de posicionamento de texto. [`PositioningMode`](../positioningmode/) O modo padrão é Legado. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Define ou obtém o algoritmo de quebra de palavras. Veja WordWrapMode e IsWordWrap. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Adiciona uma imagem à página especificada do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Adiciona uma imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Adiciona uma imagem à página especificada do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Adiciona uma imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Adiciona uma imagem à página especificada do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Adiciona uma imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Adiciona uma imagem à página especificada do documento PDF nas coordenadas especificadas. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Adiciona uma imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Não implementado. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Não implementado. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Não implementado. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Fecha o objeto PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Salva o documento PDF no fluxo especificado. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Salva o documento PDF no arquivo especificado. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)