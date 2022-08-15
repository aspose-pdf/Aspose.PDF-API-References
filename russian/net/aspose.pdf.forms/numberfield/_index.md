---
title: NumberField
second_title: Aspose.PDF для справочника API .NET
description: Текстовое поле с указанными допустимыми символами
type: docs
weight: 3090
url: /ru/net/aspose.pdf.forms/numberfield/
---
## NumberField class

Текстовое поле с указанными допустимыми символами

```csharp
public class NumberField : TextBoxField
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NumberField](numberfield#constructor)() | Инициализирует новый экземпляр[`NumberField`](../numberfield) класс. |
| [NumberField](numberfield#constructor_1)(Document, Rectangle) | Инициализирует новый экземпляр[`NumberField`](../numberfield) класс. |
| [NumberField](numberfield#constructor_2)(Page, Rectangle) | Инициализирует новый экземпляр[`NumberField`](../numberfield) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Получает действия аннотации. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| [AllowedChars](../../aspose.pdf.forms/numberfield/allowedchars) { get; set; } | Получает или устанавливает разрешенные символы. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Получает или задает альтернативное имя поля (альтернативное имя поля , которое должно использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). Альтернативное имя используется в качестве всплывающей подсказки поля в Adobe Acrobat . |
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
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs) { get; set; } | Получает или устанавливает флаг, указывающий, что поле разделено на интервальные позиции. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Получает полное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Получает или задает высоту аннотации. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Режим выделения аннотаций. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку на фрагмент (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Получает или устанавливает логическое значение, указывающее, является ли это поле нетерминальным полем, т.е. группой полей. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. Значение по умолчанию — false. (для создания pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац создаваться на новой странице. Значение по умолчанию — false. |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для создания PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Свойство для поддержки генератора. Используется, когда поле добавляется в верхний или нижний колонтитул. Если true, это поле будет создано один раз и его внешний вид будет виден на всех страницах документа. Если false, для каждой страницы документа будет создано отдельное поле. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Возвращает true, если словарь синхронизирован. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Получает подполе, содержащееся в этом поле, по имени подполя. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Получает или задает имя сопоставления поля, которое должно использоваться при экспорте данных поля интерактивной формы из документа. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания PDF-файла) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen) { get; set; } | Получает или задает максимальную длину текста в поле. |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline) { get; set; } | Получает или устанавливает многострочный флаг поля. Если Multiline имеет значение true, поле может содержать несколько строк текста. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Получает или задает имя аннотации на странице. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Действие, которое должно быть выполнено при активации аннотации. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Получает индекс страницы, содержащей это поле. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Получает родительскую аннотацию. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Получает или задает частичное имя поля. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Получает или устанавливает статус поля только для чтения. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Получает или задает прямоугольник поля. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Получает или устанавливает обязательный статус поля. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable) { get; set; } | Получает или устанавливает прокручиваемый флаг поля. Если true поле можно прокручивать. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck) { get; set; } | Получает или устанавливает флаг проверки орфографии для поля. Если истина, поле должно быть проверено на правописание. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Получает словарь внешнего вида аннотации. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Объект синхронизации. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Получает или устанавливает порядок табуляции поля. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment) { get; set; } | Получает или задает вертикальное выравнивание текста для аннотации. |
| override [Value](../../aspose.pdf.forms/textboxfield/value) { get; set; } | Получает или устанавливает значение поля. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Принимает посетителей. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode)(string) | Добавляет в поле штрих-код 128. Значение поля будет изменено на код, и поле станет доступным только для чтения. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage)(Image) | Добавляет изображение в ресурсы поля и рисует его. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Обновить параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Копирует подполя этого поля в массив, начиная с указанного индекса. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Удаляет это поле и размещает его значение прямо на странице. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Возвращает перечислитель содержащихся полей. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Повторно вычисляет все вычисляемые поля формы. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Установить положение поля. |

### Смотрите также

* class [TextBoxField](../textboxfield)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
