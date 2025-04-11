---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragmentState. Representa um estado de texto de um fragmento de texto
type: docs
weight: 10970
url: /pt/net/aspose.pdf.text/textfragmentstate/
---
## Classe TextFragmentState

Representa um estado de texto de um fragmento de texto.

```csharp
public sealed class TextFragmentState : TextState
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Inicializa uma nova instância do objeto `TextFragmentState` com o objeto [`TextFragment`](../textfragment/) especificado. Esta inicialização do `TextFragmentState` não é suportada. TextFragmentState está disponível apenas com a propriedade [`TextState`](../textfragment/textstate/). |

## Propriedades

| Nome | Descrição |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Define a cor de fundo do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Obtém ou define o espaçamento entre caracteres do texto, representado pelo objeto [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Obtém ou define a origem das coordenadas do texto. Se a origem das coordenadas for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se a origem das coordenadas for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor de Descent da fonte for muito grande, o texto pode ser renderizado mais alto do que outras fontes. Nesse caso, a origem das coordenadas BaseLine pode ser selecionada para uma melhor renderização do texto. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Obtém ou define se a borda do retângulo de texto desenhado está ativada. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Obtém ou define a fonte do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Obtém ou define o tamanho da fonte do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Define o estilo da fonte do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Obtém ou define a cor do primeiro plano do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Obtém ou define opções de formatação. A configuração das opções será eficaz apenas em cenários de geração. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal para o texto. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Obtém ou define a escala horizontal do texto, representado pelo objeto [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Obtém ou define a invisibilidade do texto. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Obtém ou define o espaçamento entre linhas do texto. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Obtém ou define o modo de renderização do texto. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Obtém ou define o ângulo de rotação em graus. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Obtém ou define o texto riscado, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Obtém ou define a cor das operações de contorno da renderização do [`TextFragment`](../textfragment/) (texto de contorno, borda do retângulo) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Obtém ou define o subscrito do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Obtém ou define o sobrescrito do texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Obtém os tab stops para o texto. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Obtém ou define o sublinhado para o texto, representado pelo objeto [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Obtém ou define o espaçamento entre palavras do texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Aplica configurações de outro textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Verifica se a string de entrada pode ser colocada dentro do retângulo definido. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mede a altura do caractere. (2 métodos) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mede a string. |

## Campos

| Nome | Descrição |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valor padrão de tabulação nas larguras do caractere de espaço da fonte padrão. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Você pode colocar esta tag no texto para declarar a tabulação. |

## Observações

Fornece uma maneira de alterar as seguintes propriedades do texto: fonte ([`Font`](./font/) propriedade) tamanho da fonte ([`FontSize`](./fontsize/) propriedade) estilo da fonte ([`FontStyle`](./fontstyle/) propriedade) cor do primeiro plano ([`ForegroundColor`](./foregroundcolor/) propriedade) cor de fundo ([`BackgroundColor`](./backgroundcolor/) propriedade) Observe que a alteração das propriedades do `TextFragmentState` pode alterar a coleção interna [`Segments`](../textfragment/segments/) porque o TextFragment é um objeto agregado e pode reorganizar segmentos internos ou mesclá-los em um único segmento. Se sua necessidade é deixar a coleção [`Segments`](../textfragment/segments/) inalterada, altere os segmentos internos individualmente.

## Exemplos

O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto [`TextState`](../textstate/).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [Document](../../aspose.pdf/document/)
* classe [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)