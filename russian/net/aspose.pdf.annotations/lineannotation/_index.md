---
title: LineAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Класс представляющий аннотацию строки.
type: docs
weight: 600
url: /ru/net/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class

Класс, представляющий аннотацию строки.

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LineAnnotation](lineannotation#constructor)(Document, Point, Point) | Конструктор для использования с генератором. |
| [LineAnnotation](lineannotation#constructor_1)(Page, Rectangle, Point, Point) | Создает новую линейную аннотацию на указанной странице. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset) { get; set; } | Получает или задает смещение текста подписи от его нормального положения. |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition) { get; set; } | Получает или задает положение заголовка аннотации. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Получает дату и время создания аннотации. |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending) { get; set; } | Получает или задает конечную точку строки. |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle) { get; set; } | Получает или задает стиль окончания для конечной точки линии. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку на фрагмент (для генератора pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Ссылка на аннотацию, на которую эта аннотация является «ответом». Обе аннотации должны быть на одной странице документа. |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent) { get; set; } | Получает или задает назначение аннотации строки. |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor) { get; set; } | Получает или задает внутренний цвет аннотации. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. Значение по умолчанию — false. (для создания pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац создаваться на новой странице. Значение по умолчанию — false. |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для создания PDF) |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline) { get; set; } | Получает или задает длину линии выноски. |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension) { get; set; } | Получает или задает длину продолжения линии выноски. |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset) { get; set; } | Получает или задает смещение линии выноски. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания PDF-файла) |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure) { get; set; } | Единицы измерения, указанные для этой аннотации. |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Получает или задает постоянное значение непрозрачности, используемое при рисовании аннотации. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Строка, указывающая связь («тип ответа») между этой аннотацией и аннотацией, указанной InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Получает или задает строку форматированного текста, которая будет отображаться во всплывающем окне при открытии аннотации. |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption) { get; set; } | Получает или устанавливает логический флаг, определяющий, должно ли содержимое отображаться как заголовок. |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting) { get; set; } | Получает или задает начальную точку линии. |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle) { get; set; } | Получает или задает стиль окончания линии для начальной точки линии. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Получает текст, представляющий описание объекта. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Получает или задает текст, который должен отображаться в строке заголовка аннотации. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept)(AnnotationSelector) | Разрешает посетителю обрабатывать аннотацию. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize)(Matrix) | Обновляет начальную и конечную точки в соответствии с преобразованием матрицы. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |

### Смотрите также

* class [MarkupAnnotation](../markupannotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
