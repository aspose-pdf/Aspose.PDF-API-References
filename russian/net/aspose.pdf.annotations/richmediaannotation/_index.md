---
title: Class RichMediaAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.RichMediaAnnotation. Класс описывает RichMediaAnnotation, который позволяет встраивать видео/аудио данные в PDF документ
type: docs
weight: 2480
url: /ru/net/aspose.pdf.annotations/richmediaannotation/
---
## Класс RichMediaAnnotation

Класс описывает RichMediaAnnotation, который позволяет встраивать видео/аудио данные в PDF документ.

```csharp
public class RichMediaAnnotation : Annotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Page, Rectangle) | Инициализирует RichMediaAnnotation. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Получает список действий аннотации. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | Событие, которое активирует приложение. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или устанавливает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или устанавливает характеристики границы аннотации. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или устанавливает цвет аннотации. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | Данные содержимого Rich Media. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или устанавливает текст аннотации. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | Устанавливает или получает переменные flash, которые передаются в плеер. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | Устанавливает или получает пользовательский flash плеер для воспроизведения видео/аудио данных. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Получает полное квалифицированное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Получает или устанавливает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или устанавливает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или устанавливает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или устанавливает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или устанавливает внешний отступ для абзаца (для генерации pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или устанавливает дату и время, когда аннотация была недавно изменена. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или устанавливает имя аннотации на странице. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Получает индекс страницы, содержащей аннотацию. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Получает или устанавливает прямоугольник аннотации. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или устанавливает выравнивание текста для аннотации. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | Получает или устанавливает тип содержимого. Возможные значения: Audio, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или устанавливает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или устанавливает целочисленное значение, указывающее Z-упорядочение графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(AnnotationSelector) | Принимает посетителя для этой аннотации. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Stream) | Добавляет пользовательские именованные данные (например, необходимые для flash-скрипта). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Stream) | Устанавливает поток содержимого. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Stream) | Устанавливает постер аннотации. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | Обновляет данные с указанными параметрами. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | Событие, которое активирует аннотацию. |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | Тип мультимедиа. |

### См. также

* класс [Annotation](../annotation/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)