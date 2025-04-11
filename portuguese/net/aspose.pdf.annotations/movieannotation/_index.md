---
title: Class MovieAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.MovieAnnotation. Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e através dos alto-falantes. Quando a anotação é ativada, o filme é reproduzido.
type: docs
weight: 2110
url: /pt/net/aspose.pdf.annotations/movieannotation/
---
## Classe MovieAnnotation

Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e através dos alto-falantes. Quando a anotação é ativada, o filme é reproduzido.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Construtor para usar com o Gerador. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Cria uma nova anotação de Som na página especificada. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtém a lista de ações da anotação. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtém ou define o estado de aparência atual da anotação. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Obtém o tipo de anotação. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtém o dicionário de aparência da anotação. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Obtém ou define a largura e altura da caixa delimitadora do filme, em pixels. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtém ou define as características da borda da anotação. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtém as características da anotação. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtém ou define a cor da anotação. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtém ou define o texto da anotação. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Obtém ou define uma especificação de arquivo identificando um arquivo de filme auto-descritivo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Sinais da anotação. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtém o nome totalmente qualificado da anotação. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtém ou define a altura da anotação. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtém ou define a data e hora em que a anotação foi recentemente modificada. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtém ou define o nome da anotação na página. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtém o índice da página que contém a anotação. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Obtém ou define um sinalizador ou fluxo que especifica se e como uma imagem de pôster representando o filme deve ser exibida. Se verdadeiro, a imagem do pôster deve ser recuperada do arquivo do filme; se for falso, nenhum pôster deve ser exibido. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtém ou define o retângulo da anotação. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Obtém ou define o número de graus pelo qual o filme deve ser girado no sentido horário em relação à página. O valor deve ser um múltiplo de 90. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtém o dicionário de aparência da anotação. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtém ou define o alinhamento do texto para a anotação. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Obtém ou define o título da anotação de filme. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtém ou define a largura da anotação. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Aceita um objeto visitante para processar a anotação. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instância. Método virtual. Sempre retorna nulo. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Coloca o conteúdo da anotação diretamente na página, o objeto de anotação será removido. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Retorna o retângulo da anotação levando em consideração a rotação da página. |

### Veja Também

* classe [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)