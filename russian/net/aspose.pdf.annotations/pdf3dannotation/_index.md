---
title: PDF3DAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Класс PDF3DАннотация. Этот класс не может быть унаследован.
type: docs
weight: 770
url: /ru/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation class

Класс PDF3DАннотация. Этот класс не может быть унаследован.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation#constructor)(Page, Rectangle, PDF3DArtwork) | Инициализирует новый экземпляр класса[`PDF3DAnnotation`](../pdf3dannotation). |
| [PDF3DAnnotation](pdf3dannotation#constructor_1)(Page, Rectangle, PDF3DArtwork, PDF3DActivation) | Инициализирует новый экземпляр класса[`PDF3DAnnotation`](../pdf3dannotation). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/pdf3dannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Content](../../aspose.pdf.annotations/pdf3dannotation/content) { get; set; } | Получает или задает содержимое. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [LightingScheme](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme) { get; } | Получает схему освещения. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или устанавливает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Pdf3DArtwork](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork) { get; } | Получает 3D-графику. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Получает или задает прямоугольник аннотации. |
| [RenderMode](../../aspose.pdf.annotations/pdf3dannotation/rendermode) { get; } | Получает режим рендеринга. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [ViewArray](../../aspose.pdf.annotations/pdf3dannotation/viewarray) { get; } | Получает массив представлений. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pdf3dannotation/accept)(AnnotationSelector) | Принимает посетителей для обработки аннотаций. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с преобразованием матрицы. |
| [ClearImagePreview](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview)() | Очищает предварительный просмотр изображения. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [GetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview)() | Получает предварительный просмотр изображения. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [SetDefaultViewIndex](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex)(int) | Устанавливает индекс представления по умолчанию. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview)(Stream) | Устанавливает предварительный просмотр изображения. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview_1)(string) | Устанавливает предварительный просмотр изображения. |

### Смотрите также

* class [Annotation](../annotation)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
