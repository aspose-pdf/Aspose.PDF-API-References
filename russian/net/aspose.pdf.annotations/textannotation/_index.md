---
title: "Класс TextAnnotation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Annotations.TextAnnotation класс. Представляет текстовую аннотацию, которая является стикером, прикреплённым к точке в PDF‑документе."
type: docs
weight: 2750
url: /ru/net/aspose.pdf.annotations/textannotation/
---
## TextAnnotation class

Представляет текстовую аннотацию, являющуюся «липкой заметкой», прикреплённой к точке в PDF‑документе.

```csharp
public sealed class TextAnnotation : MarkupAnnotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextAnnotation](textannotation/#constructor)(Document) | Конструктор аннотации, когда используется в Generator. |
| [TextAnnotation](textannotation/#constructor_1)(Page, Rectangle) | Создаёт новую Text аннотацию на указанной странице. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/textannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или задаёт характеристики границы annotation. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или задает текст аннотации. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Получает дату и время создания annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Получает полностью квалифицированное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [Icon](../../aspose.pdf.annotations/textannotation/icon/) { get; set; } | Получает или задаёт значок, используемый для отображения аннотации. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Ссылка на annotation, к которой данная annotation является "ответом". Обе annotations должны находиться на одной Page документа Document. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или задает имя аннотации на странице. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Получает или задаёт постоянное значение непрозрачности, используемое при отрисовке annotation. |
| [Open](../../aspose.pdf.annotations/textannotation/open/) { get; set; } | Получает или задаёт флаг, указывающий, должна ли аннотация изначально отображаться открытой. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Всплывающая annotation для ввода или редактирования текста, связанного с этой annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Получает или задает прямоугольник аннотации. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Строка, указывающая отношение ("тип ответа") между этой annotation и той, которая указана в InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Получает или задаёт строку форматированного текста, отображаемую во всплывающем окне при открытии annotation. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Получает текст, представляющий описание объекта. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Получает или задаёт текстовую метку, которая будет отображаться в заголовке popup window annotation’s, когда он открыт и активен. Эта запись должна идентифицировать пользователя, добавившего annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/textannotation/accept/)(AnnotationSelector) | Принимает объект посетителя для обработки annotation. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textannotation/changeafterresize/)(Matrix) | Переопределяет определение в базовом классе пустым телом. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Очищает состояние и модель состояния аннотации. Например, очищает статус проверки для аннотации. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удалён. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учётом поворота страницы. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Получает состояние аннотации. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Получает модель состояния аннотации. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Устанавливает состояние Marked и Unmarked для аннотации. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не относятся к Review StateModel. Состояние задаётся пользователем, создавшим целевую аннотацию. Значение берётся из свойства Title целевой аннотации. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Устанавливает состояние проверки для аннотации. Состояния Marked и Unmarked игнорируются, так как они не относятся к Review StateModel. Примечание: состояние хранится в другой текстовой аннотации, у которой есть ключи state и statemodel. |

### См. также

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


