---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextState. Representa um estado de texto de um texto
type: docs
weight: 11070
url: /pt/net/aspose.pdf.text/textstate/
---
## Classe TextState

Representa um estado de texto de um texto

```csharp
public class TextState
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextState](textstate/#constructor)() | Cria um objeto de estado de texto. |
| [TextState](textstate/#constructor_2)(Color) | Cria um objeto de estado de texto com especificação de cor de primeiro plano. |
| [TextState](textstate/#constructor_1)(double) | Cria um objeto de estado de texto com especificação de tamanho de fonte. |
| [TextState](textstate/#constructor_4)(string) | Cria um objeto de estado de texto com especificação de família de fonte. |
| [TextState](textstate/#constructor_3)(Color, double) | Cria um objeto de estado de texto com especificação de cor de primeiro plano e tamanho de fonte. |
| [TextState](textstate/#constructor_6)(string, double) | Cria um objeto de estado de texto com especificação de família de fonte e tamanho de fonte. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Cria um objeto de estado de texto com especificação de família de fonte e estilo de fonte. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Define a cor de fundo do texto. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Obtém ou define o espaçamento entre caracteres do texto. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Obtém ou define a origem de coordenadas do texto. Se a origem de coordenadas for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se a origem de coordenadas for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor de Descent da fonte for muito grande, o texto pode ser renderizado mais alto do que outras fontes. Nesse caso, a origem de coordenadas BaseLine pode ser selecionada para uma melhor renderização do texto. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Obtém ou define a fonte do texto. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Obtém ou define o tamanho da fonte do texto. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Define o estilo da fonte do texto. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Obtém ou define a cor de primeiro plano do texto. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal para o texto. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Obtém ou define a escala horizontal do texto. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Obtém ou define a invisibilidade do texto. Isso basicamente reflete o estado do [`RenderingMode`](./renderingmode/), exceto em alguns casos especiais (como recorte). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Obtém ou define o espaçamento entre linhas do texto. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Obtém ou define o modo de renderização do texto. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Obtém ou define o texto riscado, representado pelo objeto [`TextSegment`](../textsegment/) |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Obtém ou define a cor de primeiro plano do texto. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Obtém ou define o subscrito do texto. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Obtém ou define o sobrescrito do texto. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Obtém ou define o sublinhado para o texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Obtém ou define o espaçamento entre palavras do texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Aplica configurações de outro textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Mede a altura do caractere. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Mede a string. |

## Campos

| Nome | Descrição |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valor padrão de tabulação nas larguras do caractere de espaço da fonte padrão. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Você pode colocar esta tag no texto para declarar a tabulação. |

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)