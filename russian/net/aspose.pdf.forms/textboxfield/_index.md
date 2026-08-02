---
title: "Класс TextBoxField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Forms.TextBoxField. Класс, представляющий текстовое поле."
type: docs
weight: 5440
url: /ru/net/aspose.pdf.forms/textboxfield/
---
## TextBoxField class

Класс, представляющий поле текстового блока.

```csharp
public class TextBoxField : Field
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextBoxField](textboxfield/#constructor_1)(Document) | Конструктор, который следует использовать с Generator. |
| [TextBoxField](textboxfield/#constructor_2)(Document, Rectangle) | Конструктор поля TextBox. |
| [TextBoxField](textboxfield/#constructor_3)(Page, Rectangle) | Конструктор поля TextBox. |
| [TextBoxField](textboxfield/#constructor_4)(Page, Rectangle[]) | Конструктор поля TextBox. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Получает действия аннотации. (2 свойства) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Получает или задает альтернативное имя поля (альтернативное имя поля, которое должно использоваться вместо фактического имени поля везде, где поле идентифицируется в пользовательском интерфейсе). Альтернативное имя используется как всплывающая подсказка поля в Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Получает или задает индекс этой аннотации на Page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или задает характеристики границы аннотации. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или задает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или задает текст аннотации. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Получает количество подполей в этом поле. (Например, количество элементов в поле переключателя). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Получает или задает внешний вид по умолчанию поля. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Получает или задает экспортируемый флаг поля. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Получает или задает флаг, указывающий, разделено ли поле на позиционные интервалы. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Получает полностью квалифицированное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Получает или задает высоту аннотации. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Режим подсветки аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Получает или задает логическое значение, указывающее, является ли это поле нетерминальным, т.е. группой полей. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Свойство для поддержки Generator. Используется, когда поле добавляется в заголовок или нижний колонтитул. Если true, это поле будет создано один раз, и его внешний вид будет виден на всех страницах Document. Если false, отдельное поле будет создано для каждой страницы Document. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Возвращает true, если словарь синхронизирован. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Получает подполе, содержащееся в этом поле, по имени подполе. (2 индексатора) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Получает или задает имя отображения поля, которое будет использоваться при экспорте данных интерактивных форм из Document. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Получает или задает максимальную длину текста в поле. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Получает или задает флаг многострочности поля. Если Multiline равно true, поле может содержать несколько строк текста. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или задает имя аннотации на странице. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Действие, которое будет выполнено при активации аннотации. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Получает индекс страницы, содержащей это поле. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Получает родительскую аннотацию. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Получает или задает частичное имя поля. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Получает или задает статус только для чтения поля. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Получает или задает прямоугольник поля. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Получает или задает обязательный статус поля. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Получает или задает флаг прокручиваемости поля. Если true, поле можно прокручивать. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Получает или задает флаг проверки орфографии для поля. Если true, поле должно быть проверено на орфографию. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Объект синхронизации. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Получает или задает порядок табуляции поля. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание текста для аннотации. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Получает или задает значение поля. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Принимает посетителя. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Добавляет штрихкод 128 в поле. Значение поля будет заменено на код, и поле станет только для чтения. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | Добавляет изображение в ресурсы поля и отрисовывает его. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Копирует подполе(ы) этого поля в массив, начиная с указанного индекса. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Выполняет указанное действие JavaScript для поля. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Экспортирует указанное поле формы PDF в формат JSON и записывает результат в предоставленный поток. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Экспортирует указанное поле формы PDF в формат JSON и записывает результат в указанный файл. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Экспортирует содержимое указанного поля в поток JSON. Значения полей‑кнопок не экспортируются. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Удаляет это поле и размещает его значение непосредственно на странице. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Возвращает имя состояния "checked" в соответствии с существующими именами состояний. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Возвращает перечислитель содержащихся полей. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учётом поворота страницы. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Импортирует данные в указанные поля из потока JSON, основываясь на точном совпадении полных имён полей. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Импортирует данные в указанное поле из потока JSON, используя полное имя, указанное в переменной 'fieldFullNameInJSON', для сопоставления. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Пересчитывает все вычисляемые поля в форме. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Устанавливает позицию поля. |

### См. также

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


