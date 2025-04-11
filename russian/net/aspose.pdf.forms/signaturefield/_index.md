---
title: Class SignatureField
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Forms.SignatureField. Представляет поле формы для подписи
type: docs
weight: 5290
url: /ru/net/aspose.pdf.forms/signaturefield/
---
## Класс SignatureField

Представляет поле формы для подписи.

```csharp
public sealed class SignatureField : Field
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SignatureField](signaturefield/#constructor)(Document, Rectangle) | Инициализирует новый экземпляр класса `SignatureField`. |
| [SignatureField](signaturefield/#constructor_1)(Page, Rectangle) | Инициализирует новый экземпляр класса `SignatureField`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Получает действия аннотации. (2 свойства) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или задает текущее состояние внешнего вида аннотации. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Получает или задает альтернативное имя поля (Альтернативное имя поля, которое будет использоваться вместо фактического имени поля, где бы оно ни идентифицировалось в пользовательском интерфейсе). Альтернативное имя используется в качестве подсказки для поля в Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Получает или задает индекс этой аннотации на странице. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или задает характеристики границы аннотации. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или задает цвет аннотации. |
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
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или задает имя аннотации на странице. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Действие, которое должно быть выполнено, когда аннотация активируется. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Получает индекс страницы, содержащей это поле. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Получает родительскую аннотацию. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Получает или задает частичное имя поля. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Получает или задает статус только для чтения поля. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Получает или задает прямоугольник поля. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Получает или задает статус обязательности поля. |
| [Signature](../../aspose.pdf.forms/signaturefield/signature/) { get; } | Получает объект подписи. Этот объект содержит данные подписи в соответствии с криптографическими стандартами с открытым ключом. Классы [`PKCS1`](../pkcs1/), [`PKCS7`](../pkcs7/) и [`PKCS7Detached`](../pkcs7detached/) представляют все поддерживаемые типы объектов подписи. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Объект синхронизации. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Получает или задает порядок табуляции поля. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или задает выравнивание текста для аннотации. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Получает или задает значение поля. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или задает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Принимает посетителя. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Копирует подполя этого поля в массив, начиная с указанного индекса. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Выполняет указанное действие JavaScript для поля. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Экспортирует указанное поле формы PDF в формат JSON и записывает результат в предоставленный поток. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Экспортирует указанное поле формы PDF в формат JSON и записывает результат в указанный файл. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Экспортирует содержимое указанного поля в поток JSON. Значения полей кнопок не экспортируются. |
| [ExtractCertificate](../../aspose.pdf.forms/signaturefield/extractcertificate/)() | Извлекает единственный сертификат X.509 в формате DER в виде потока. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage)() | Извлекает изображение подписи в виде потока, закодированного в jpeg. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage_1)(ImageFormat) | Извлекает изображение подписи в виде закодированного потока. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Удаляет это поле и помещает его значение непосредственно на страницу. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Возвращает имя состояния "отмечено" в соответствии с существующими именами состояний. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Возвращает перечислитель содержащихся полей. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Импортирует данные в указанные поля из потока JSON на основе точного совпадения полных имен полей. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Импортирует данные в указанное поле из потока JSON, используя полное имя, указанное в переменной 'fieldFullNameInJSON' для сопоставления. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Пересчитывает все вычисляемые поля на форме. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Устанавливает позицию поля. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign)(Signature) | Подписывает документ, используя это поле подписи. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign_1)(Signature, Stream, string) | Подписывает документ, используя это поле подписи. |

### См. также

* класс [Field](../field/)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../)