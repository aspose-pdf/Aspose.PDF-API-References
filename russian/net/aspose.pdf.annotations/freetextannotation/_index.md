---
title: FreeTextAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Представляет аннотацию произвольного текста которая отображает текст непосредственно на странице. В отличие от обычной текстовой аннотации аннотация произвольного текста не имеет открытого или закрытого состояния вместо того чтобы отображаться во всплывающем окне текст всегда виден.
type: docs
weight: 430
url: /ru/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

Представляет аннотацию произвольного текста, которая отображает текст непосредственно на странице. В отличие от обычной текстовой аннотации, аннотация произвольного текста не имеет открытого или закрытого состояния; вместо того, чтобы отображаться во всплывающем окне, текст всегда виден.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FreeTextAnnotation](freetextannotation#constructor)(Document, DefaultAppearance) | Конструктор для использования с генератором. |
| [FreeTextAnnotation](freetextannotation#constructor_1)(Page, Rectangle, DefaultAppearance) | Создает новую аннотацию FreeText на указанной странице. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout) { get; set; } | Массив точек, указывающих линию выноски. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Получает дату и время создания аннотации. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance) { get; set; } | Получает или задает строку оформления по умолчанию, которая будет использоваться при форматировании текста. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject) { get; } | Объект, представляющий внешний вид аннотации FreeText по умолчанию. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle) { get; set; } | Получает или задает строку стиля по умолчанию. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle) { get; set; } | Получает или задает стиль окончания строки для конечной точки строки. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Ссылка на аннотацию, на которую эта аннотация является "ответом". Обе аннотации должны быть на одной странице документа. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent) { get; set; } | Получает или задает назначение аннотации произвольного текста. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification) { get; set; } | Получает или задает код, определяющий форму квадрирования (выравнивания), которая будет использоваться при отображении текста аннотации. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или устанавливает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Получает или задает постоянное значение непрозрачности, используемое при рисовании аннотации. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Строка, определяющая связь ("тип ответа") между этой аннотацией и аннотацией, указанной InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Получает или задает строку форматированного текста, которая будет отображаться во всплывающем окне при открытии аннотации. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate) { get; set; } | Угол поворота аннотации. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle) { get; set; } | Получает или задает стиль окончания строки для конечной точки строки. OЭто свойство устарело, используйте EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Получает текст, представляющий описание объекта. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle) { get; set; } | Прямоугольник, описывающий числовые различия между двумя прямоугольниками:записью Rect аннотации и прямоугольником, содержащимся внутри этого прямоугольника. Во внутреннем прямоугольнике должен отображаться текст аннотации. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle) { get; set; } | Получает или задает стиль текста во внешнем виде. при изменении стиля текста обновляется внешний вид текста. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Получает или задает текст, который должен отображаться в строке заголовка аннотации. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept)(AnnotationSelector) | Принимает объект посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с преобразованием матрицы. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |

### Смотрите также

* class [MarkupAnnotation](../markupannotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
