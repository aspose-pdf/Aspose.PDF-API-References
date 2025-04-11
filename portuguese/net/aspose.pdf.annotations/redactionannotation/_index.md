---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.RedactionAnnotation. Representa a anotação de redacção
type: docs
weight: 2400
url: /pt/net/aspose.pdf.annotations/redactionannotation/
---
## Classe RedactionAnnotation

Representa a anotação de redacção.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | Construtor para RedactionAnnotation. Para uso no Gerador. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | Construtor para RedactAnnotation. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtém a lista de ações da anotação. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtém ou define o estado de aparência atual da anotação. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Obtém o tipo de anotação. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtém o dicionário de aparência da anotação. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtém ou define as características da borda da anotação. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Obtém ou define a cor da borda que é desenhada quando a redacção não está ativa. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtém as características da anotação. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtém ou define a cor da anotação. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtém ou define o texto da anotação. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtém a data e hora em que a anotação foi criada. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Obtém ou define a string de aparência padrão a ser usada na formatação do texto. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Obtém ou define a cor para preencher a anotação. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Sinais da anotação. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Obtém ou define o tamanho da fonte para OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtém o nome totalmente qualificado da anotação. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtém ou define a altura da anotação. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Uma referência à anotação que esta anotação está "em resposta a". Ambas as anotações devem estar na mesma página do documento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtém ou define a data e hora em que a anotação foi recentemente modificada. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtém ou define o nome da anotação na página. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtém ou define o valor de opacidade constante a ser usado na pintura da anotação. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Obtém ou define o texto a ser impresso na anotação de redacção. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtém o índice da página que contém a anotação. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotação pop-up para inserir ou editar o texto associado a esta anotação. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Um array de números 8xN especificando as coordenadas da região de conteúdo que se destina a ser removida. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtém ou define o retângulo da anotação. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Se verdadeiro, o texto sobreposto será repetido na anotação. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Uma string que especifica a relação (o "tipo de resposta") entre esta anotação e uma especificada por InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtém ou define uma string de texto rico a ser exibida na janela pop-up quando a anotação é aberta. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtém o dicionário de aparência da anotação. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtém o texto que representa a descrição do objeto. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Obtém ou define. Alinhamento do Texto Sobreposto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtém ou define o alinhamento do texto para a anotação. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtém ou define um texto que deve ser exibido na barra de título da anotação. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtém ou define a largura da anotação. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Aceita um objeto visitante para processar a anotação. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Limpa o estado e o modelo de estado da anotação. Por exemplo, limpa o status de revisão de uma anotação. Note que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instância. Método virtual. Sempre retorna nulo. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Achata a anotação, ou seja, remove a anotação e adiciona sua |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtém o estado da anotação. Note que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtém o modelo de estado da anotação. Note que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Achata a anotação e redige o conteúdo da página (ou seja, remove texto e imagem sob a anotação redigida) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Define o estado Marcado e Desmarcado para a anotação. Note que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao Modelo de Estado de Revisão. O estado é definido pelo usuário que criou a anotação alvo. O valor é retirado da propriedade Título da anotação alvo. Note que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao Modelo de Estado de Revisão. Note que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |

### Veja Também

* classe [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)