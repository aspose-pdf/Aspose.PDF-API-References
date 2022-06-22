---
title: RichMediaAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Класс описывает RichMediaAnnotation которая позволяет вставлять видео/аудиоданные в документ PDF.
type: docs
weight: 1030
url: /ru/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

Класс описывает RichMediaAnnotation, которая позволяет вставлять видео/аудиоданные в документ PDF.

```csharp
public class RichMediaAnnotation : Annotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation)(Page, Rectangle) | Инициализирует RichMediaAnnotation. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon) { get; set; } | Событие, активирующее приложение. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content) { get; } | Данные мультимедийного контента. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables) { get; set; } | Устанавливает или получает flash-переменные, которые передаются игроку. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer) { get; set; } | Устанавливает или получает собственный флэш-плеер для воспроизведения видео/аудиоданных. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или устанавливает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type) { get; set; } | Получает или задает тип содержимого. Возможные значения:Аудио, Видео. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept)(AnnotationSelector) | Принимает посетителей для этой аннотации. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata)(string, Stream) | Добавить пользовательские именованные данные (например, необходимые для flash-скрипта). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с преобразованием матрицы. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent)(string, Stream) | Установить поток контента. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter)(Stream) | Установить постер аннотации. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update)() | Обновляет данные с указанными параметрами. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ActivationEvent](richmediaannotation.activationevent) | Событие, активирующее аннотацию. |
| enum [ContentType](richmediaannotation.contenttype) | Тип мультимедиа. |

### Смотрите также

* class [Annotation](../annotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
