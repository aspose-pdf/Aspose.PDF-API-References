---
title: "MarkupAnnotation.SetReviewState"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод MarkupAnnotation. Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не относятся к модели Review StateModel. Обратите внимание на состояние, сохранённое в другой текстовой аннотации, которая имеет ключи state и statemodel."
type: docs
weight: 140
url: /ru/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не относятся к Review StateModel. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| state | AnnotationState | Статус для назначения. |
| userName | String | Имя пользователя, отображаемое в заголовке комментариев. Имя может совпадать с именем в заголовке Title целевой аннотации или отличаться, если статус установлен другим пользователем. |

### См. также

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не относятся к Review StateModel. Состояние задаётся пользователем, создавшим целевую аннотацию. Значение берётся из свойства Title целевой аннотации. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel.

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


