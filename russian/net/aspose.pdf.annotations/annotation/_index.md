---
title: "Класс Annotation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Annotations.Annotation class. Класс, представляющий объект аннотации"
type: docs
weight: 1500
url: /ru/net/aspose.pdf.annotations/annotation/
---
## Annotation class

Класс, представляющий объект аннотации.

```csharp
public abstract class Annotation : BaseParagraph
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или задает характеристики границы аннотации. [`Border`](./border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или задает текст аннотации. |
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
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Получает или задает прямоугольник аннотации. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | Если true, внешний вид аннотации будет обновлен перед преобразованием PF-документа в изображение. Это позволяет корректно преобразовать поля, но, вероятно, требует больше времени. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | Если это свойство установлено в true, шрифты будут добавлены в документ как подмножества. Значение по умолчанию — true. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | Принимает посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удалён. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учётом поворота страницы. |

### См. также

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


