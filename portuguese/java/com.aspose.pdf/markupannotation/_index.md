---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe abstrata que representa anotação de marcação."
type: docs
weight: 2870
url: /pt/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Classe abstrata que representa anotação de marcação.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Construtor |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [clearState](#clearState--) | Limpa o estado e o modelo de estado da anotação. Por exemplo, limpa o status de revisão de uma anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel. |
| [getCreationDate](#getCreationDate--) | Obtém a data e hora em que a anotação foi criada. |
| [getInReplyTo](#getInReplyTo--) | Uma referência à anotação à qual esta anotação está "em resposta a". Ambas as anotações devem estar na mesma página do documento. |
| [getOpacity](#getOpacity--) | Obtém o valor constante de opacidade a ser usado ao renderizar a anotação. |
| [getPopup](#getPopup--) | Anotação pop-up para inserir ou editar o texto associado a esta anotação. |
| [getReplyType](#getReplyType--) | Uma string que especifica o relacionamento (o "tipo de resposta") entre esta anotação e a especificada por InReplyTo. |
| [getRichText](#getRichText--) | Obtém uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Obtém uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta. |
| [getState](#getState--) | Obtém o estado da anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel. |
| [getStateModel](#getStateModel--) | Obtém o modelo de estado da anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel. |
| [getSubject](#getSubject--) | Obtém o texto que representa a descrição do objeto. |
| [getTitle](#getTitle--) | Obtém um rótulo de texto que deve ser exibido na barra de título da janela pop-up da anotação quando aberta e ativa. Esta entrada deve identificar o usuário que adicionou a anotação. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Obtém a data e hora em que a anotação foi criada. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Uma referência à anotação à qual esta anotação está "em resposta a". Ambas as anotações devem estar na mesma página do documento. |
| [setMarkedState](#setMarkedState-boolean-) | Define o estado Marcado e Não Marcado para a anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel. |
| [setOpacity](#setOpacity-double-) | Define o valor constante de opacidade a ser usado ao renderizar a anotação. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Anotação pop-up para inserir ou editar o texto associado a esta anotação. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | Uma string que especifica o relacionamento (o "tipo de resposta") entre esta anotação e a especificada por InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Define o estado de revisão para uma anotação. Os estados Marcado e Não Marcado são ignorados, pois não pertencem ao Review StateModel. O estado é definido pelo usuário que criou a anotação alvo. O valor é obtido da propriedade Title da anotação alvo. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Define o estado de revisão para uma anotação. Os estados Marcado e Não Marcado são ignorados, pois não pertencem ao Review StateModel. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel. |
| [setRichText](#setRichText-java.lang.String-) | Define uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta. |
| [setSubject](#setSubject-java.lang.String-) | Define o texto que representa a descrição do objeto. |
| [setTitle](#setTitle-java.lang.String-) | Define um rótulo de texto que deve ser exibido na barra de título da janela pop-up da anotação quando aberta e ativa. Esta entrada deve identificar o usuário que adicionou a anotação. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Construtor

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Construtor

### clearState {#clearState--}
```
public final void clearState()
```

Limpa o estado e o modelo de estado da anotação. Por exemplo, limpa o status de revisão de uma anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtém a data e hora em que a anotação foi criada.

**Returns:**
Objeto Date

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Uma referência à anotação à qual esta anotação está "em resposta a". Ambas as anotações devem estar na mesma página do documento.

**Returns:**
Valor da anotação

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtém o valor constante de opacidade a ser usado ao renderizar a anotação.

**Returns:**
valor double

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Anotação pop-up para inserir ou editar o texto associado a esta anotação.

**Returns:**
Valor da PopupAnnotation

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

Uma string que especifica o relacionamento (o "tipo de resposta") entre esta anotação e a especificada por InReplyTo.

**Returns:**
Valor ReplyType @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Obtém uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta.

**Returns:**
valor String

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Obtém uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta.

**Returns:**
valor String

### getState {#getState--}
```
public final AnnotationState getState()
```

Obtém o estado da anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel.

**Returns:**
Estado da anotação.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Obtém o modelo de estado da anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel.

**Returns:**
Modelo de estado da anotação.

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtém o texto que representa a descrição do objeto.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtém um rótulo de texto que deve ser exibido na barra de título da janela pop-up da anotação quando aberta e ativa. Esta entrada deve identificar o usuário que adicionou a anotação.

**Returns:**
valor String

### setCreationDate {#setCreationDate-java.util.Date-}
Obtém a data e hora em que a anotação foi criada.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Uma referência à anotação à qual esta anotação está "em resposta a". Ambas as anotações devem estar na mesma página do documento.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Define o estado Marcado e Não Marcado para a anotação. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| marcado |  | Verdadeiro se define o estado Marcado, e falso se define o estado Desmarcado. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Define o valor constante de opacidade a ser usado ao renderizar a anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Anotação pop-up para inserir ou editar o texto associado a esta anotação.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
Uma string que especifica o relacionamento (o "tipo de resposta") entre esta anotação e a especificada por InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Define o estado de revisão para uma anotação. Os estados Marcado e Não Marcado são ignorados, pois não pertencem ao Review StateModel. O estado é definido pelo usuário que criou a anotação alvo. O valor é obtido da propriedade Title da anotação alvo. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Define o estado de revisão para uma anotação. Os estados Marcado e Não Marcado são ignorados, pois não pertencem ao Review StateModel. Observação, o estado armazenado em outra anotação de texto que possui chaves state e statemodel.

### setRichText {#setRichText-java.lang.String-}
Define uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta.

### setSubject {#setSubject-java.lang.String-}
Define o texto que representa a descrição do objeto.

### setTitle {#setTitle-java.lang.String-}
Define um rótulo de texto que deve ser exibido na barra de título da janela pop-up da anotação quando aberta e ativa. Esta entrada deve identificar o usuário que adicionou a anotação.
