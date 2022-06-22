---
title: ButtonField
second_title: Aspose.PDF для справочника API .NET
description: Класс представляет поле кнопки.
type: docs
weight: 2920
url: /ru/net/aspose.pdf.forms/buttonfield/
---
## ButtonField class

Класс представляет поле кнопки.

```csharp
public class ButtonField : Field
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ButtonField](buttonfield#constructor)() | Конструктор поля кнопки для Генератора. |
| [ButtonField](buttonfield#constructor_1)(Document, Rectangle) | Конструктор ButtonField. |
| [ButtonField](buttonfield#constructor_2)(Page, Rectangle) | Конструктор ButtonField. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Получает действия аннотации. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| [AlternateCaption](../../aspose.pdf.forms/buttonfield/alternatecaption) { get; set; } | Получает или задает альтернативный заголовок кнопки, который будет отображаться при нажатии кнопки мыши в ее активной области. |
| [AlternateIcon](../../aspose.pdf.forms/buttonfield/alternateicon) { get; set; } | Получает или задает альтернативную иконку, которая будет отображаться при нажатии кнопки мыши в ее активной области. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Получает или задает альтернативное имя поля (Альтернативное поле имя, которое должно использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). Альтернативное имя используется в качестве подсказки к полю в Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Получает или задает индекс этой аннотации на странице. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Получает или задает характеристики границы аннотации.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Получает или задает текст аннотации. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Получает или задает количество подполей в этом поле. (Например, количество элементов в поле переключателя). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Получает или задает внешний вид поля по умолчанию. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Получает или устанавливает экспортируемый флаг поля. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Режим выделения аннотаций. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [IconFit](../../aspose.pdf.forms/buttonfield/iconfit) { get; } | Получает объект, соответствующий значку, указывающий, как значок аннотации виджета должен отображаться в пределах его прямоугольника аннотации. |
| [ICPosition](../../aspose.pdf.forms/buttonfield/icposition) { get; set; } | Получает или задает положение заголовка значка. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Получает или устанавливает логическое значение, указывающее, является ли это поле нетерминальным полем, т.е. группой полей. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. По умолчанию false. (для генерации pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Свойство для поддержки Генератора. Используется, когда поле добавляется в верхний или нижний колонтитул. Если true, это поле будет создано один раз и его внешний вид будет виден на всех страницах документа. Если false, для каждой страницы документа будет создано отдельное поле. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Возвращает true, если словарь синхронизирован. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Получает подполе, содержащееся в этом поле, по имени подполя. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Получает или задает имя сопоставления поля, которое будет использоваться при экспорте данных поля интерактивной формы из документа. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или устанавливает дату и время последнего изменения аннотации. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| [NormalCaption](../../aspose.pdf.forms/buttonfield/normalcaption) { get; set; } | Получает или устанавливает обычный заголовок. |
| [NormalIcon](../../aspose.pdf.forms/buttonfield/normalicon) { get; set; } | Получает или задает обычную иконку кнопки, которая должна отображаться, когда она не взаимодействует с пользователем. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Действие, которое должно выполняться при активации аннотации. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Получает индекс страницы, содержащей это поле. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Получает родительскую аннотацию. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Получает или задает частичное имя поля. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Получает или устанавливает статус поля только для чтения. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Получает или задает прямоугольник поля. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Получает или устанавливает обязательный статус поля. |
| [RolloverCaption](../../aspose.pdf.forms/buttonfield/rollovercaption) { get; set; } | Получает или устанавливает заголовок кнопки, который будет отображаться, когда пользователь наводит курсор в его активную область, не нажимая кнопку мыши. |
| [RolloverIcon](../../aspose.pdf.forms/buttonfield/rollovericon) { get; set; } | Получает или задает иконку прокрутки кнопки, которая будет отображаться, когда пользователь перемещает курсор в ее активную область, не нажимая кнопку мыши. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Объект синхронизации. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Получает или устанавливает порядок табуляции поля. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| virtual [Value](../../aspose.pdf.forms/field/value) { get; set; } | Получает или устанавливает значение поля. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Принимает посетителей. |
| [AddImage](../../aspose.pdf.forms/buttonfield/addimage)(Image) | Добавляет изображение в ресурсы поля и рисует его. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с преобразованием матрицы. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Копирует подполя этого поля в массив, начиная с указанного индекса. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Удаляет это поле и размещает его значение прямо на странице. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Возвращает перечислитель содержащихся полей. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Повторно вычисляет все вычисляемые поля в форме. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Установить положение поля. |

### Смотрите также

* class [Field](../field)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
