---
title: SoundAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Представляет звуковую аннотацию содержащую звук записанный с микрофона компьютера или импортированный из файла.
type: docs
weight: 1080
url: /ru/net/aspose.pdf.annotations/soundannotation/
---
## SoundAnnotation class

Представляет звуковую аннотацию, содержащую звук, записанный с микрофона компьютера или импортированный из файла.

```csharp
public sealed class SoundAnnotation : MarkupAnnotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SoundAnnotation](soundannotation#constructor)(Page, Rectangle, string) | Создает новую звуковую аннотацию на указанной странице. |
| [SoundAnnotation](soundannotation#constructor_1)(Page, Rectangle, string, SoundSampleData) | Создает новую звуковую аннотацию на указанной странице. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/soundannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Получает дату и время создания аннотации. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [Icon](../../aspose.pdf.annotations/soundannotation/icon) { get; set; } | Получает или задает значок, который будет использоваться при отображении аннотации. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Ссылка на аннотацию, на которую эта аннотация является "ответом". Обе аннотации должны быть на одной странице документа. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или устанавливает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Получает или задает постоянное значение непрозрачности, используемое при рисовании аннотации. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Строка, определяющая связь ("тип ответа") между этой аннотацией и аннотацией, указанной InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Получает или задает строку форматированного текста, которая будет отображаться во всплывающем окне при открытии аннотации. |
| [SoundData](../../aspose.pdf.annotations/soundannotation/sounddata) { get; } | Получает звуковой объект, определяющий звук, который будет воспроизводиться при активации аннотации. |
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
| override [Accept](../../aspose.pdf.annotations/soundannotation/accept)(AnnotationSelector) | Принимает объект посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с преобразованием матрицы. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |

### Смотрите также

* class [MarkupAnnotation](../markupannotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
