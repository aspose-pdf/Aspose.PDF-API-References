---
title: MovieAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Представляет аннотацию к фильму содержащую анимированную графику и звук для воспроизведения на экране компьютера и через динамики. При активации аннотации воспроизводится фильм.
type: docs
weight: 730
url: /ru/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Представляет аннотацию к фильму, содержащую анимированную графику и звук для воспроизведения на экране компьютера и через динамики. При активации аннотации воспроизводится фильм.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MovieAnnotation](movieannotation#constructor)(Document, string) | Конструктор для использования с генератором. |
| [MovieAnnotation](movieannotation#constructor_1)(Page, Rectangle, string) | Создает новую звуковую аннотацию на указанной странице. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect) { get; set; } | Получает или задает ширину и высоту ограничивающей рамки фильма в пикселях. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [File](../../aspose.pdf.annotations/movieannotation/file) { get; set; } | Получает или задает спецификацию файла, идентифицирующую файл фильма с самоописанием. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку на фрагмент (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. Значение по умолчанию — false. (для создания pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац создаваться на новой странице. Значение по умолчанию — false. |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для создания PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания PDF-файла) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster) { get; set; } | Получает или задает флаг или поток, указывающий, будет ли отображаться изображение постера, представляющее фильм, и каким образом. Если true, изображение постера должно быть получено из файла фильма; если оно ложно, постер не будет отображаться. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate) { get; set; } | Получает или задает количество градусов, на которое фильм должен быть повернут по часовой стрелке относительно страницы. Значение должно быть кратно 90. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [Title](../../aspose.pdf.annotations/movieannotation/title) { get; set; } | Получает или задает заголовок аннотации к фильму. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept)(AnnotationSelector) | Принимает объект посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |

### Смотрите также

* class [Annotation](../annotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
