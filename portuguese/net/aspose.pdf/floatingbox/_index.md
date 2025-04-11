---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class.
type: docs
weight: 4870
url: /pt/net/aspose.pdf/floatingbox/
---
## Classe FloatingBox

```csharp
public class FloatingBox : BaseParagraph
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Inicializa uma nova instância da classe `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Inicializa uma nova instância da classe `FloatingBox` com largura e altura especificadas. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Obtém ou define um objeto [`Color`](../color/) que indica a cor de fundo da caixa flutuante. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Obtém ou define a imagem de fundo para a página (apenas para gerador, não preenchido ao ler o documento). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Obtém ou define um objeto [`BorderInfo`](../borderinfo/) que indica as informações da borda da caixa flutuante. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Obtém ou define informações da coluna |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Obtém ou define um valor float que indica a altura da caixa flutuante. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtém ou define um alinhamento horizontal do parágrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo precisa ser repetido na próxima página. O valor padrão é falso. O atributo é válido apenas quando o próprio parágrafo e o objeto referenciado por seu ReferenceParagraphID estão incluídos em RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Obtém ou define a coordenada esquerda da tabela. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Obtém ou define um objeto [`MarginInfo`](../margininfo/) que indica o preenchimento da caixa flutuante. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Obtém ou define uma coleção [`Paragraphs`](./paragraphs/) que indica todos os parágrafos na célula. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Especifica a variante para determinar a localização da FloatingBox na página. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Obtém ou define a coordenada superior da tabela. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Obtém ou define um valor float que indica a largura da caixa flutuante. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Clona um novo objeto `FloatingBox`. Os parágrafos na caixa flutuante não são clonados. |

### Veja Também

* classe [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)