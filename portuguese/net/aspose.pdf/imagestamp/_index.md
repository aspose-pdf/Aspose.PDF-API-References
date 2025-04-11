---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImageStamp. Representa um carimbo gráfico
type: docs
weight: 5930
url: /pt/net/aspose.pdf/imagestamp/
---
## Classe ImageStamp

Representa um carimbo gráfico.

```csharp
public sealed class ImageStamp : Stamp
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Inicializa uma nova instância da classe `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Cria um carimbo de imagem a partir da imagem no arquivo especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Obtém ou define o texto alternativo para o carimbo de imagem. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Define ou obtém um valor booleano que indica se o conteúdo é carimbado como fundo. Se o valor for verdadeiro, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é falso, o conteúdo do carimbo é colocado na parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtém ou define a margem inferior do carimbo. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Obtém ou define a altura da imagem. Definir esta imagem permite escalar a imagem verticalmente. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal do carimbo na página. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Obtém o fluxo de imagem usado para o carimbo. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtém ou define a margem esquerda do carimbo. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtém ou define um valor para indicar a opacidade do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtém ou define um valor para indicar a opacidade do contorno do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtém ou define um valor da largura do contorno do carimbo. Por padrão, o valor é 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Obtém ou define a qualidade do carimbo de imagem em porcentagem. Valores válidos são 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtém ou define a margem direita do carimbo. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Define ou obtém a rotação do conteúdo do carimbo de acordo com os valores de [`Rotation`](../rotation/). Nota. Esta propriedade é para definir ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtém ou define o ângulo de rotação do carimbo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtém ou define a margem superior do carimbo. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtém ou define o alinhamento vertical do carimbo na página. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Obtém ou define a largura da imagem. Definir esta propriedade permite escalar a imagem horizontalmente. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Obtém e define a coordenada horizontal do carimbo, começando da esquerda. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Obtém e define a coordenada vertical do carimbo, começando de baixo. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fator de zoom do carimbo. Permite escalar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. Definir esta propriedade altera tanto as propriedades ZoomX quanto ZoomY. Se ZoomX e ZoomY forem diferentes, então a propriedade Zoom retorna o valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fator de zoom horizontal do carimbo. Permite escalar o carimbo horizontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fator de zoom vertical do carimbo. Permite escalar o carimbo verticalmente. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Retorna o ID do carimbo. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Adiciona um carimbo gráfico na página. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Define o ID do carimbo. |

### Veja Também

* classe [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)