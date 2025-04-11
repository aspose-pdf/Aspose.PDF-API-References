---
title: Class MovieAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.MovieAnnotation. Представляет аннотацию фильма, которая содержит анимационную графику и звук, которые будут представлены на экране компьютера и через динамики. Когда аннотация активируется, фильм воспроизводится.
type: docs
weight: 2110
url: /ru/net/aspose.pdf.annotations/movieannotation/
---
## Класс MovieAnnotation

Представляет аннотацию фильма, которая содержит анимационную графику и звук, которые будут представлены на экране компьютера и через динамики. Когда аннотация активируется, фильм воспроизводится.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Конструктор для использования с Генератором. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Создает новую аннотацию звука на указанной странице. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или устанавливает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Получает или устанавливает ширину и высоту ограничивающего прямоугольника фильма в пикселях. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или устанавливает характеристики границы аннотации. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или устанавливает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или устанавливает текст аннотации. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Получает или устанавливает спецификацию файла, идентифицирующую самодокументируемый файл фильма. |
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
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Получает или устанавливает флаг или поток, указывающий, будет ли и как изображение постера, представляющее фильм, отображаться. Если true, изображение постера будет извлечено из файла фильма; если false, постер не будет отображаться. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Получает или устанавливает прямоугольник аннотации. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Получает или устанавливает количество градусов, на которое фильм должен быть повернут по часовой стрелке относительно страницы. Значение должно быть кратно 90. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или устанавливает выравнивание текста для аннотации. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Получает или устанавливает заголовок аннотации фильма. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или устанавливает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или устанавливает целочисленное значение, указывающее Z- порядок графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Принимает объект посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |

### См. также

* класс [Annotation](../annotation/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)