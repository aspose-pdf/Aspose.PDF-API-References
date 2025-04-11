---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PageNumberStamp. Representa um carimbo de número de página e é usado para numerar páginas
type: docs
weight: 8230
url: /pt/net/aspose.pdf/pagenumberstamp/
---
## Classe PageNumberStamp

Representa um carimbo de número de página e é usado para numerar páginas.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Inicializa uma nova instância da classe `PageNumberStamp`. O formato é definido como "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Cria PageNumberStamp por texto formatado. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Inicializa uma nova instância da classe `PageNumberStamp`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Ajusta automaticamente a precisão do tamanho da fonte. Valor padrão: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Se habilitado, o tamanho da fonte será ajustado automaticamente para caber no retângulo do carimbo de tamanho: [`Width`](../textstamp/width/) e [`Height`](../textstamp/height/). A largura e altura padrão são derivadas do retângulo da página. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Define ou obtém um valor bool que indica se o conteúdo é carimbado como fundo. Se o valor for verdadeiro, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é falso, o conteúdo do carimbo é colocado na parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtém ou define a margem inferior do carimbo. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Esta propriedade determina como o carimbo é desenhado na página. Se Draw = verdadeiro, o carimbo é desenhado como operadores gráficos e se draw = falso, o carimbo é desenhado como texto. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Tamanho real da fonte após o carimbo ter sido colocado. (Pode diferir do tamanho da fonte inicial fornecido através do construtor se a opção 'AutoAdjustFontSizeToFitStampRectangle' estiver habilitada.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Valor de string para carimbar números de página. O valor deve incluir o caractere '#' que é substituído pelo número da página no processo de carimbo. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Altura desejada do carimbo na página. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal do carimbo na página. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Define a justificação do texto. Se esta propriedade for definida como verdadeira, as bordas esquerda e direita do texto são alinhadas. Valor padrão: falso. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtém ou define a margem esquerda do carimbo. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Altura máxima da linha para a opção WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Obtém ou define o modo que define o comportamento caso as fontes não contenham os caracteres solicitados. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Estilo de numeração usado por este carimbo. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtém ou define um valor para indicar a opacidade do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtém ou define um valor para indicar a opacidade do contorno do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtém ou define um valor da largura do contorno do carimbo. Por padrão, o valor é 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtém ou define a margem direita do carimbo. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Define ou obtém a rotação do conteúdo do carimbo de acordo com os valores de [`Rotation`](../rotation/). Nota. Esta propriedade é para definir ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtém ou define o ângulo de rotação do carimbo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Define a escala do texto. Se esta propriedade for definida como verdadeira e o valor da Largura for especificado, o texto será escalado para caber na largura especificada. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Obtém ou define o valor do número da página inicial. Outras páginas serão numeradas a partir deste valor. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Alinhamento do texto dentro do carimbo. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Obtém as propriedades do texto do carimbo. Veja [`TextState`](../textstamp/textstate/) para detalhes. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtém ou define a margem superior do carimbo. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Define a origem das coordenadas para colocar o texto. Se TreatYIndentAsBaseLine = verdadeiro (padrão quando Draw = verdadeiro), o valor de YIndent será tratado como a linha de base do texto. Se TreatYIndentAsBaseLine = falso (padrão quando Draw = falso), o valor de YIndent será tratado como a parte inferior (linha de descida) do texto. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Obtém ou define o valor da string que é usado como carimbo na página. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtém ou define o alinhamento vertical do carimbo na página. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Largura desejada do carimbo na página. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Obtém ou define o modo de quebra de linha para a renderização do texto. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordenada horizontal do carimbo, começando da esquerda. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordenada vertical do carimbo, começando de baixo. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fator de zoom do carimbo. Permite escalar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. A definição desta propriedade altera tanto as propriedades ZoomX quanto ZoomY. Se ZoomX e ZoomY forem diferentes, a propriedade Zoom retorna o valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fator de zoom horizontal do carimbo. Permite escalar o carimbo horizontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fator de zoom vertical do carimbo. Permite escalar o carimbo verticalmente. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Retorna o ID do carimbo. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Adiciona o número da página. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Define o ID do carimbo. |

### Veja Também

* classe [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)