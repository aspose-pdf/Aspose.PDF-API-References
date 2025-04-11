---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: Método MarkupAnnotation. Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao modelo de estado de revisão. Observe o estado armazenado em outra anotação de texto que possui chaves de estado e modelo de estado.
type: docs
weight: 140
url: /pt/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao modelo de estado de revisão. Observe, o estado armazenado em outra anotação de texto que possui chaves de estado e modelo de estado.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| state | AnnotationState | Status para atribuição. |
| userName | String | O nome de usuário que aparece no cabeçalho dos comentários. O nome pode ser o mesmo que o nome no Título da anotação de destino ou diferente se o status for definido por outro usuário. |

### Veja Também

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Define o estado de revisão para uma anotação. Os estados Marcado e Desmarcado são ignorados, pois não pertencem ao modelo de estado de revisão. O estado é definido pelo usuário que criou a anotação de destino. O valor é retirado da propriedade Título da anotação de destino. Observe, o estado armazenado em outra anotação de texto que possui chaves de estado e modelo de estado.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| state | AnnotationState | Status para atribuição. |

### Veja Também

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)