---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfPageStamp. Classe representa um carimbo que usa a página PDF como carimbo
type: docs
weight: 8420
url: /pt/net/aspose.pdf/pdfpagestamp/
---
## Classe PdfPageStamp

Classe representa um carimbo que usa a página PDF como carimbo.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Construtor da classe PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Cria um carimbo de página PDF a partir da página especificada no documento a partir do fluxo. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Cria um carimbo de página PDF a partir da página especificada do documento no arquivo especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Define ou obtém um valor booleano que indica se o conteúdo é carimbado como fundo. Se o valor for verdadeiro, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é falso, o conteúdo do carimbo é colocado na parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtém ou define a margem inferior do carimbo. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Altura desejada do carimbo na página. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal do carimbo na página. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtém ou define a margem esquerda do carimbo. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtém ou define um valor para indicar a opacidade do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtém ou define um valor para indicar a opacidade do contorno do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtém ou define um valor da largura do contorno do carimbo. Por padrão, o valor é 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Obtém ou define a página que será usada como carimbo. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtém ou define a margem direita do carimbo. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Define ou obtém a rotação do conteúdo do carimbo de acordo com os valores de [`Rotation`](../rotation/). Nota. Esta propriedade é para definir ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, a propriedade Rotate retorna Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtém ou define o ângulo de rotação do carimbo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtém ou define a margem superior do carimbo. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtém ou define o alinhamento vertical do carimbo na página. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Largura desejada do carimbo na página. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordenada horizontal do carimbo, começando da esquerda. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordenada vertical do carimbo, começando de baixo. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fator de zoom do carimbo. Permite escalar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. A definição desta propriedade altera ambas as propriedades ZoomX e ZoomY. Se ZoomX e ZoomY forem diferentes, a propriedade Zoom retorna o valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fator de zoom horizontal do carimbo. Permite escalar o carimbo horizontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fator de zoom vertical do carimbo. Permite escalar o carimbo verticalmente. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Retorna o ID do carimbo. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Coloca o carimbo na página especificada. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Define o ID do carimbo. |

### Veja Também

* classe [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)