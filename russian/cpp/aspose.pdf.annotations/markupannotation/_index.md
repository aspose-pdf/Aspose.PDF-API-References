---
title: "Aspose::Pdf::Annotations::MarkupAnnotation class"
linktitle: "MarkupAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::MarkupAnnotation class. Абстрактный класс, представляющий разметку аннотации в C++."
type: docs
weight: 6100
url: /ru/cpp/aspose.pdf.annotations/markupannotation/
---
## MarkupAnnotation class


Абстрактный класс, представляющий разметочную аннотацию.

```cpp
class MarkupAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [ClearState](./clearstate/)() | Очищает состояние и модель состояния аннотации. Например, очищает статус проверки аннотации. [Note](../../aspose.pdf/note/), состояние, хранящееся в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [get_CreationDate](./get_creationdate/)() | Получает дату и время создания аннотации. |
| [get_InReplyTo](./get_inreplyto/)() | Ссылка на аннотацию, к которой данная аннотация является "ответом". Обе аннотации должны находиться на одной странице документа. |
| [get_Opacity](./get_opacity/)() | Получает постоянное значение непрозрачности, используемое при отрисовке аннотации. |
| [get_Popup](./get_popup/)() | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| [get_ReplyType](./get_replytype/)() | Строка, указывающая отношение ("тип ответа") между этой аннотацией и той, которая указана в InReplyTo. |
| [get_RichText](./get_richtext/)() | Получает строку форматированного текста, отображаемую во всплывающем окне при открытии аннотации. |
| [get_Subject](./get_subject/)() | Получает текст, представляющий описание объекта. |
| [get_Title](./get_title/)() override | Получает текстовую метку, которая будет отображаться в заголовке всплывающего окна аннотации, когда оно открыто и активно. Эта запись должна идентифицировать пользователя, добавившего аннотацию. |
| [GetState](./getstate/)() | Получает состояние аннотации. [Note](../../aspose.pdf/note/), состояние, хранящееся в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [GetStateModel](./getstatemodel/)() | Получает модель состояния аннотации. [Note](../../aspose.pdf/note/), состояние, хранящееся в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [MarkupAnnotation](./markupannotation/)(const System::SharedPtr\<Document\>\&) | Конструктор разметочной аннотации. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Получает дату и время создания аннотации. |
| [set_InReplyTo](./set_inreplyto/)(const System::SharedPtr\<Annotation\>\&) | Ссылка на аннотацию, к которой данная аннотация является "ответом". Обе аннотации должны находиться на одной странице документа. |
| [set_Opacity](./set_opacity/)(double) | Устанавливает постоянное значение непрозрачности, используемое при отрисовке аннотации. |
| [set_Popup](./set_popup/)(const System::SharedPtr\<PopupAnnotation\>\&) | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| [set_ReplyType](./set_replytype/)(Aspose::Pdf::Annotations::ReplyType) | Строка, указывающая отношение ("тип ответа") между этой аннотацией и той, которая указана в InReplyTo. |
| [set_RichText](./set_richtext/)(const System::String\&) | Устанавливает строку форматированного текста, отображаемую во всплывающем окне при открытии аннотации. |
| [set_Subject](./set_subject/)(const System::String\&) | Получает текст, представляющий описание объекта. |
| [set_Title](./set_title/)(System::String) override | Устанавливает текстовую метку, которая будет отображаться в заголовке всплывающего окна аннотации, когда оно открыто и активно. Эта запись должна идентифицировать пользователя, добавившего аннотацию. |
| [SetMarkedState](./setmarkedstate/)(bool) | Устанавливает состояние Marked и Unmarked для аннотации. [Note](../../aspose.pdf/note/), состояние, хранящееся в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [SetReviewState](./setreviewstate/)(AnnotationState, const System::String\&) | Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не относятся к Review StateModel. [Note](../../aspose.pdf/note/), состояние, хранящееся в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [SetReviewState](./setreviewstate/)(AnnotationState) | Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не принадлежат Review StateModel. Состояние устанавливается пользователем, создавшим целевую аннотацию. Значение берётся из свойства Title целевой аннотации. [Note](../../aspose.pdf/note/), состояние хранится в другой текстовой аннотации, которая имеет ключи state и statemodel. |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
