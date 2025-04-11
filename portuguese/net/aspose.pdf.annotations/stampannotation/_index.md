---
title: Class StampAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.StampAnnotation. Representa a anotação de carimbo de borracha. Este tipo de anotação exibe texto ou gráficos que parecem ter sido carimbados na página com um carimbo de borracha.
type: docs
weight: 2610
url: /pt/net/aspose.pdf.annotations/stampannotation/
---
## Classe StampAnnotation

Representa a anotação de carimbo de borracha. Este tipo de anotação exibe texto ou gráficos que parecem ter sido carimbados na página com um carimbo de borracha.

```csharp
public sealed class StampAnnotation : MarkupAnnotation
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [StampAnnotation](stampannotation/#constructor)(Document) | Construtor |
| [StampAnnotation](stampannotation/#constructor_1)(Page, Rectangle) | Cria uma nova anotação de carimbo na página especificada. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtém a lista de ações da anotação. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtém ou define o estado de aparência atual da anotação. |
| override [AnnotationType](../../aspose.pdf.annotations/stampannotation/annotationtype/) { get; } | Obtém o tipo de anotação. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtém o dicionário de aparência da anotação. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtém ou define as características da borda da anotação. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtém as características da anotação. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtém ou define a cor da anotação. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtém ou define o texto da anotação. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtém a data e hora em que a anotação foi criada. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Sinais da anotação. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtém o nome totalmente qualificado da anotação. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtém ou define a altura da anotação. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [Icon](../../aspose.pdf.annotations/stampannotation/icon/) { get; set; } | Obtém ou define o ícone para o carimbo de borracha. |
| [Image](../../aspose.pdf.annotations/stampannotation/image/) { get; set; } | Obtém ou define a imagem da anotação. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Uma referência à anotação que esta anotação está "em resposta a". Ambas as anotações devem estar na mesma página do documento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtém ou define a data e hora em que a anotação foi recentemente modificada. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtém ou define o nome da anotação na página. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtém ou define o valor de opacidade constante a ser usado na pintura da anotação. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtém o índice da página que contém a anotação. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotação pop-up para inserir ou editar o texto associado a esta anotação. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtém ou define o retângulo da anotação. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Uma string que especifica a relação (o "tipo de resposta") entre esta anotação e uma especificada por InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtém ou define uma string de texto rico a ser exibida na janela pop-up quando a anotação é aberta. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtém o dicionário de aparência da anotação. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtém o texto que representa a descrição do objeto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtém ou define o alinhamento do texto para a anotação. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtém ou define um texto que deve ser exibido na barra de título da anotação. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtém ou define a largura da anotação. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. O ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/stampannotation/accept/)(AnnotationSelector) | Aceita [`AnnotationSelector`](../annotationselector/) visitante ao navegar pela coleção de anotações. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Limpa o estado e o modelo de estado da anotação. Por exemplo, limpa o status de revisão de uma anotação. Observe que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instância. Método virtual. Sempre retorna nulo. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Coloca o conteúdo da anotação diretamente na página, o objeto da anotação será removido. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtém o estado da anotação. Observe que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtém o modelo de estado da anotação. Observe que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Define o estado Marcado e Desmarcado para a anotação. Observe que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao Modelo de Estado de Revisão. O estado é definido pelo usuário que criou a anotação de destino. O valor é retirado da propriedade Título da anotação de destino. Observe que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao Modelo de Estado de Revisão. Observe que o estado é armazenado em outra anotação de texto que possui chaves de estado e modelo de estado. |

## Exemplos

O próximo trecho de código demonstra como adicionar 2 carimbos na primeira página do documento pdf. O documento de entrada vem de inFile e as alterações são salvas em outFile. O primeiro carimbo tem o ícone NotForPublicRelease e o segundo vem com a imagem de rubber.jpg.

```csharp
Document document = new Document(inFile);
StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease);
stamp1.Rect = new Rectangle(100, 100, 120, 120)
document.Pages[1].Annotations.Add(stamp1);
StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open));
stamp2.Rect = new Rectangle(200, 200, 220, 220)
document.Pages[1].Annotations.Add(stamp2);
document.Save(outFile);
```

### Veja Também

* classe [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)