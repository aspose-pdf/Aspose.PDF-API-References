---
title: "MarkupAnnotation.SetReviewState"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo MarkupAnnotation. Imposta lo stato di revisione per un'annotazione. Gli stati Marcato e Non Marcato sono ignorati poiché non appartengono al Review StateModel. Nota lo stato memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel."
type: docs
weight: 140
url: /it/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Imposta lo stato di revisione per un'annotazione. Gli stati Marked e Unmarked sono ignorati poiché non appartengono al Review StateModel. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stato | AnnotationState | Stato per l'assegnazione. |
| userName | String | Il nome utente che appare nell'intestazione dei commenti. Il nome può essere lo stesso del nome nel Title dell'annotazione di destinazione o diverso se lo stato è impostato da un altro utente. |

### Vedi anche

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Imposta lo stato di revisione per un'annotazione. Gli stati Marked e Unmarked sono ignorati poiché non appartengono al Review StateModel. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stato | AnnotationState | Stato per l'assegnazione. |

### Vedi anche

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


