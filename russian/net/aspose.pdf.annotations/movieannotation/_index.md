---
title: "Класс MovieAnnotation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Annotations.MovieAnnotation. Представляет аннотацию фильма, содержащую анимированную графику и звук, которые отображаются на экране компьютера и воспроизводятся через динамики. При активации аннотации фильм воспроизводится."
type: docs
weight: 2200
url: /ru/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Представляет аннотацию фильма, содержащую анимированную графику и звук, которые отображаются на экране компьютера и воспроизводятся через динамики. При активации аннотации фильм воспроизводится.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Конструктор для использования с Generator. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Создаёт новую звуковую аннотацию на указанной странице. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Получает или задаёт ширину и высоту ограничивающего прямоугольника фильма в пикселях. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или задаёт характеристики границы annotation. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или задает текст аннотации. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Получает или задаёт спецификацию файла, идентифицирующую самодокументируемый файл фильма. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Получает полностью квалифицированное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Получает или задает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или задает имя аннотации на странице. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Получает или задаёт флаг или поток, указывающий, будет ли и как отображаться постер-изображение, представляющее фильм. Если true, постер будет получен из файла фильма; если false, постер отображаться не будет. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Получает или задает прямоугольник аннотации. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Получает или задаёт количество градусов, на которое фильм будет повернут по часовой стрелке относительно страницы. Значение должно быть кратным 90. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Получает или задает заголовок аннотации фильма. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Принимает объект посетителя для обработки annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удалён. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учётом поворота страницы. |

### См. также

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


