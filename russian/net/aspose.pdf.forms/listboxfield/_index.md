---
title: Class ListBoxField
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Forms.ListBoxField. Класс представляет поле ListBox
type: docs
weight: 5130
url: /ru/net/aspose.pdf.forms/listboxfield/
---
## Класс ListBoxField

Класс представляет поле ListBox.

```csharp
public sealed class ListBoxField : ChoiceField
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ListBoxField](listboxfield/#constructor)() | Конструктор для ListBoxField, который будет использоваться в генераторе. |
| [ListBoxField](listboxfield/#constructor_1)(Document, Rectangle) | Конструктор для поля ListBox. |
| [ListBoxField](listboxfield/#constructor_2)(Page, Rectangle) | Создает новое поле ListBox. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Получает действия аннотации. (2 свойства) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Получает или задает альтернативное имя поля (Альтернативное имя поля, которое будет использоваться вместо фактического имени поля, где бы поле ни идентифицировалось в пользовательском интерфейсе). Альтернативное имя используется как подсказка поля в Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Получает или задает индекс этой аннотации на странице. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или задает характеристики границы аннотации. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или задает цвет аннотации. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Получает или задает флаг немедленного выполнения при изменении выбора. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или задает текст аннотации. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Получает количество подполей в этом поле. (Например, количество элементов в поле радиокнопки). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Получает или задает внешний вид по умолчанию для поля. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Получает или задает флаг экспортируемости поля. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Получает полное квалифицированное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Получает или задает высоту аннотации. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Режим выделения аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Получает или задает логическое значение, указывающее, является ли это поле нетерминальным полем, т.е. группой полей. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Свойство для поддержки генератора. Используется, когда поле добавляется в заголовок или нижний колонтитул. Если true, это поле будет создано один раз, и его внешний вид будет виден на всех страницах документа. Если false, для каждой страницы документа будет создано отдельное поле. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Возвращает true, если словарь синхронизирован. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Получает подполе, содержащееся в этом поле по имени подполя. (2 индексатора) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Получает или задает имя сопоставления поля, которое будет использоваться при экспорте данных интерактивного поля формы из документа. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или задает дату и время, когда аннотация была недавно изменена. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Получает или задает флаг множественного выбора. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или задает имя аннотации на странице. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Действие, которое должно быть выполнено, когда аннотация активируется. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Получает коллекцию вариантов выбора. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Получает индекс страницы, которая содержит это поле. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Получает родительскую аннотацию. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Получает или задает частичное имя поля. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Получает или задает статус только для чтения поля. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Получает или задает прямоугольник поля. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Получает или задает статус обязательности поля. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected/) { set; } | Получает или задает индекс выбранного элемента. Элементы нумеруются с 1. |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems/) { set; } | Получает или задает массив выбранных элементов в списке множественного выбора. Для списка с одиночным выбором возвращает массив с единственным элементом. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Объект синхронизации. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Получает или задает порядок табуляции поля. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex/) { get; set; } | Получает или задает индекс верхнего видимого элемента списка. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Получает или задает значение поля. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Принимает посетителя. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Добавляет новый вариант с указанным именем. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Добавляет новый вариант с указанным экспортным значением и именем. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Копирует подполе этого поля в массив, начиная с указанного индекса. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Удаляет вариант по его имени. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Выполняет указанное действие JavaScript для поля. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Экспортирует указанное поле формы PDF в формат JSON и записывает результат в предоставленный поток. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Экспортирует указанное поле формы PDF в формат JSON и записывает результат в указанный файл. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Экспортирует содержимое указанного поля в поток JSON. Значения полей кнопок не экспортируются. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Удаляет это поле и помещает его значение непосредственно на страницу. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Возвращает имя состояния "отмечено" в соответствии с существующими именами состояний. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Возвращает перечислитель содержащихся полей. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Импортирует данные в указанные поля из потока JSON на основе точного совпадения полных имен полей. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Импортирует данные в указанное поле из потока JSON, используя полное имя, указанное в переменной 'fieldFullNameInJSON' для сопоставления. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Пересчитывает все вычисляемые поля на форме. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Устанавливает позицию поля. |

### См. также

* класс [ChoiceField](../choicefield/)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../)