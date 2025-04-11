---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: Metodo MarkupAnnotation. Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non Contrassegnato vengono ignorati in quanto non appartengono al Review StateModel. Nota lo stato memorizzato in un'altra annotazione di testo che ha chiavi state e statemodel
type: docs
weight: 140
url: /it/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non Contrassegnato vengono ignorati in quanto non appartengono al Review StateModel. Nota, lo stato memorizzato in un'altra annotazione di testo che ha chiavi state e statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Stato per l'assegnazione. |
| userName | String | Il nome utente che appare nell'intestazione dei commenti. Il nome può essere lo stesso del nome nel Titolo dell'annotazione di destinazione o diverso se lo stato è impostato da un altro utente. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non Contrassegnato vengono ignorati in quanto non appartengono al Review StateModel. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato memorizzato in un'altra annotazione di testo che ha chiavi state e statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Stato per l'assegnazione. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)