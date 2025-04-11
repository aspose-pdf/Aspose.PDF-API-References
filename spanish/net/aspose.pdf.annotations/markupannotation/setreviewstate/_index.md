---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: Método MarkupAnnotation. Establece el estado de revisión para una anotación. Los estados Marcado y Desmarcado se ignoran ya que no pertenecen al modelo de estado de revisión. Tenga en cuenta el estado almacenado en otra anotación de texto que tiene claves de estado y modelo de estado.
type: docs
weight: 140
url: /es/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Establece el estado de revisión para una anotación. Los estados Marcado y Desmarcado se ignoran ya que no pertenecen al modelo de estado de revisión. Tenga en cuenta el estado almacenado en otra anotación de texto que tiene claves de estado y modelo de estado.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| state | AnnotationState | Estado para la asignación. |
| userName | String | El nombre de usuario que aparece en el encabezado de los comentarios. El nombre puede ser el mismo que el nombre en el Título de la anotación objetivo o diferente si el estado es establecido por otro usuario. |

### Ver También

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Establece el estado de revisión para una anotación. Los estados Marcado y Desmarcado se ignoran ya que no pertenecen al modelo de estado de revisión. El estado es establecido por el usuario que creó la anotación objetivo. El valor se toma de la propiedad Título de la anotación objetivo. Tenga en cuenta el estado almacenado en otra anotación de texto que tiene claves de estado y modelo de estado.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| state | AnnotationState | Estado para la asignación. |

### Ver También

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)