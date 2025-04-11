---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: Метод MarkupAnnotation. Устанавливает состояние рецензирования для аннотации. Состояния "Отмечено" и "Не отмечено" игнорируются, так как они не относятся к модели состояния рецензирования. Обратите внимание на состояние, хранящееся в другой текстовой аннотации, которая имеет ключи state и statemodel.
type: docs
weight: 140
url: /ru/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Устанавливает состояние рецензирования для аннотации. Состояния "Отмечено" и "Не отмечено" игнорируются, так как они не относятся к модели состояния рецензирования. Обратите внимание, состояние, хранящееся в другой текстовой аннотации, которая имеет ключи state и statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| state | AnnotationState | Статус для назначения. |
| userName | String | Имя пользователя, которое отображается в заголовке комментариев. Имя может совпадать с именем в заголовке целевой аннотации или отличаться, если статус установлен другим пользователем. |

### См. также

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Устанавливает состояние рецензирования для аннотации. Состояния "Отмечено" и "Не отмечено" игнорируются, так как они не относятся к модели состояния рецензирования. Состояние устанавливается пользователем, который создал целевую аннотацию. Значение берется из свойства Title целевой аннотации. Обратите внимание, состояние, хранящееся в другой текстовой аннотации, которая имеет ключи state и statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| state | AnnotationState | Статус для назначения. |

### См. также

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)