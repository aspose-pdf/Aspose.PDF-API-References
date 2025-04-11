---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.SvgExtractionOptions. Representa uma classe de opções para extrair gráficos vetoriais da página do documento pdf
type: docs
weight: 11240
url: /pt/net/aspose.pdf.vector/svgextractionoptions/
---
## Classe SvgExtractionOptions

Representa uma classe de opções para extrair gráficos vetoriais da página do documento pdf.

```csharp
public class SvgExtractionOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Obtém e define a opção para agrupar automaticamente subcaminhos em imagens. Esta opção exclui a opção [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Obtém e define a opção para extrair cada subcaminho de um documento PDF para imagens SVG separadas. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Obtém e define o retângulo delimitador que define a área de extração para a extração SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Obtém e define uma opção para a força de agrupamento de subcaminhos em imagens. Permite configurar o grau de agrupamento de subcaminhos. O valor varia de 0 a 1. Um valor de 0 corresponde à opção [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) sendo habilitada. Um valor de 1 criará uma única imagem para todos os caminhos vetoriais na página. A opção tem efeito quando [`AutoGrouping`](./autogrouping/) é falso. O valor padrão é `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Obtém ou define a largura mínima do traço que será usada no SVG resultante. Se o PDF usar uma largura de traço mais fina, ela será substituída por esta largura. O valor padrão é 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Obtém e define uma opção para verificar estritamente se os subcaminhos estão dentro do retângulo especificado em [`ExtractionAreaBound`](./extractionareabound/). Se definido como falso, então subcaminhos que não estão completamente incluídos em [`ExtractionAreaBound`](./extractionareabound/) serão extraídos. O valor padrão é `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Obtém e define uma flag que determina se o XForm encontrado nas páginas deve ser desempacotado ou não. Elementos XForm podem acabar em arquivos SVG diferentes. Apenas XForms que são renderizados por declarações Do do conteúdo da página são desempacotados. XForms aninhados não são desempacotados. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Obtém e define a opção para desempacotar apenas o XForm correspondente ao predicado especificado. |

### Veja Também

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)