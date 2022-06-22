---
title: RedactionAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Представляет аннотацию Redact.
type: docs
weight: 960
url: /ru/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

Представляет аннотацию Redact.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RedactionAnnotation](redactionannotation#constructor)(Document) | Конструктор для RedactionAnnotation. Для использования в генераторе. |
| [RedactionAnnotation](redactionannotation#constructor_1)(Page, Rectangle) | Конструктор для RedactAnnotation. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor) { get; set; } | Получает или задает цвет границы, которая рисуется, когда редактирование неактивно. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Получает дату и время создания аннотации. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance) { get; set; } | Получает или задает строку оформления по умолчанию, которая будет использоваться при форматировании текста. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor) { get; set; } | Получает или задает цвет для заполнения аннотации. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Ссылка на аннотацию, на которую эта аннотация является "ответом". Обе аннотации должны быть на одной странице документа. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или устанавливает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Получает или задает постоянное значение непрозрачности, используемое при рисовании аннотации. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext) { get; set; } | Текст для печати на отредактированной аннотации. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint) { get; set; } | Массив из 8xN чисел, указывающих координаты области контента, которую предполагается удалить. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat) { get; set; } | Если true текст наложения будет повторяться в аннотации. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Строка, определяющая связь ("тип ответа") между этой аннотацией и аннотацией, указанной InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Получает или задает строку форматированного текста, которая будет отображаться во всплывающем окне при открытии аннотации. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Получает текст, представляющий описание объекта. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment) { get; set; } | Получает или устанавливает. Выравнивание наложенного текста. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Получает или задает текст, который должен отображаться в строке заголовка аннотации. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept)(AnnotationSelector) | Принимает объект посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с преобразованием матрицы. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten)() | Выравнивает аннотацию, т.е. удаляет аннотацию и добавляет свою |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact)() | Выравнивает аннотацию и редактирует содержимое страницы (т.е. удаляет текст и изображение под отредактированной аннотацией) |

### Смотрите также

* class [MarkupAnnotation](../markupannotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
