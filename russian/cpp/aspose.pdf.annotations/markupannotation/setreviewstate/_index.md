---
title: "Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState метод"
linktitle: "SetReviewState"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState метод. Устанавливает состояние обзора для аннотации. Состояния Помечено и Не помечено игнорируются, так как они не относятся к модели состояния обзора. Состояние задаётся пользователем, создавшим целевую аннотацию. Значение берётся из свойства Title целевой аннотации. Примечание, состояние хранится в другой текстовой аннотации, которая имеет ключи state и statemodel в C++."
type: docs
weight: 2200
url: /ru/cpp/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## MarkupAnnotation::SetReviewState(AnnotationState) method


Устанавливает состояние обзора для аннотации. Состояния Помечено и Не помечено игнорируются, так как они не относятся к модели состояния обзора. Состояние задаётся пользователем, создавшим целевую аннотацию. Значение берётся из свойства Title целевой аннотации. [Примечание](../../../aspose.pdf/note/), состояние хранится в другой текстовой аннотации, которая имеет ключи state и statemodel.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| state | AnnotationState | Статус для назначения. |

## См. также

* Enum [AnnotationState](../../annotationstate/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## MarkupAnnotation::SetReviewState(AnnotationState, const System::String\&) method


Устанавливает состояние обзора для аннотации. Состояния Помечено и Не помечено игнорируются, так как они не относятся к модели состояния обзора. [Примечание](../../../aspose.pdf/note/), состояние хранится в другой текстовой аннотации, которая имеет ключи state и statemodel.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state, const System::String &userName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| state | AnnotationState | Статус для назначения. |
| userName | const System::String\& | Имя пользователя, отображаемое в заголовке комментариев. Имя может совпадать с именем в свойстве Title целевой аннотации или отличаться, если статус установлен другим пользователем. |

## См. также

* Enum [AnnotationState](../../annotationstate/)
* Class [String](../../../system/string/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
