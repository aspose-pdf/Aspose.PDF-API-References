---
title: "Класс ListBoxField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Forms.ListBoxField. Класс представляет поле ListBox."
type: docs
weight: 5250
url: /ru/net/aspose.pdf.forms/listboxfield/
---
## ListBoxField class

Класс представляет поле ListBox.

```csharp
public sealed class ListBoxField : ChoiceField
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ListBoxField](listboxfield/#constructor)() | Конструктор ListBoxField, используемый в Generator. |
| [ListBoxField](listboxfield/#constructor_1)(Document, Rectangle) | Конструктор поля ListBox. |
| [ListBoxField](listboxfield/#constructor_2)(Page, Rectangle) | Создаёт новое поле ListBox. |

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
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Получает или задаёт флаг подтверждения при изменении выбора. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или задает текст аннотации. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Получает количество подполей в этом поле. (Например, количество элементов в поле переключателя). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Получает или задает внешний вид по умолчанию поля. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Получает или задает экспортируемый флаг поля. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
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
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или задает дату и время последнего изменения аннотации. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Получает или задаёт флаг множественного выбора. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или задает имя аннотации на странице. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Действие, которое будет выполнено при активации аннотации. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Получает коллекцию вариантов выбора. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Получает индекс страницы, содержащей это поле. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Получает родительскую аннотацию. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Получает или задает частичное имя поля. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Получает или задает статус только для чтения поля. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Получает или задает прямоугольник поля. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Получает или задает обязательный статус поля. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected/) { set; } | Получает или задаёт индекс выбранного элемента. Элементы нумеруются с 1. |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems/) { set; } | Получает или задаёт массив выбранных элементов в списке с множественным выбором. Для списка с одиночным выбором возвращает массив с одним элементом. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Объект синхронизации. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Получает или задает порядок табуляции поля. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex/) { get; set; } | Получает или задаёт индекс верхнего видимого элемента списка. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Получает или задает значение поля. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Принимает посетителя. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Добавляет новую опцию с указанным именем. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Добавляет новую опцию с указанным экспортным значением и именем. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Копирует подполе(ы) этого поля в массив, начиная с указанного индекса. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Удаляет опцию по её имени. |
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

* class [ChoiceField](../choicefield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


