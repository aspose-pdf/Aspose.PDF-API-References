---
title: PageNumberStamp
second_title: Aspose.PDF для справочника API .NET
description: Представляет штамп номера страницы и используется для нумерации страниц.
type: docs
weight: 5890
url: /ru/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Представляет штамп номера страницы и используется для нумерации страниц.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PageNumberStamp](pagenumberstamp#constructor)() | Инициализирует новый экземпляр класса[`PageNumberStamp`](../pagenumberstamp). Формат установлен в "#". |
| [PageNumberStamp](pagenumberstamp#constructor_1)(FormattedText) | Создает PageNumberStamp по форматированному тексту. |
| [PageNumberStamp](pagenumberstamp#constructor_2)(string) | Инициализирует новый экземпляр класса[`PageNumberStamp`](../pagenumberstamp). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Устанавливает или получает логическое значение, указывающее, что содержимое помечается как фон. Если значение равно true, содержимое штампа размещается внизу. По умолчанию значение false, содержимое штампа кладется вверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Получает или задает нижнее поле штампа. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Это свойство определяет способ отображения штампа на странице. Если Draw = true, штамп рисуется как графические операторы, а если draw = false, то штамп рисуется как текст. |
| [Format](../../aspose.pdf/pagenumberstamp/format) { get; set; } | Строковое значение для штамповки номеров страниц. Значение должно включать символ '#', который в процессе штамповки заменяется номером страницы. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Получает или задает Горизонтальное выравнивание штампа на странице. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Определяет выравнивание текста. Если для этого свойства установлено значение true, выравниваются как левый, так и правый края текста. Значение по умолчанию:ложь. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Получает или задает левое поле штампа. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Максимальная высота строки для параметра WordWrap. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle) { get; set; } | Стиль нумерации, используемый этим штампом. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Получает или задает значение, указывающее непрозрачность штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Получает или задает значение, указывающее непрозрачность контура штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Получает или задает значение ширины контура штампа. По умолчанию значение равно 1,0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Получает или задает правое поле штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Устанавливает или получает поворот содержимого штампа в соответствии с[`Rotation`](../rotation)значениями. Примечание. Это свойство предназначено для заданных углов, кратных 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, заданный ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Получает или задает угол поворота штампа в градусах. Это свойство позволяет задать произвольный угол поворота. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Определяет масштабирование текста. Если для этого свойства установлено значение true и указано значение ширины, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber) { get; set; } | Получает или задает значение номера начальной страницы. Остальные страницы будут нумероваться, начиная с этого значения. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Выравнивание текста внутри штампа. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Получает текстовые свойства штампа. Подробнее см.[`TextState`](../textstamp/textstate). |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Получает или задает верхнее поле штампа. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая строка текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (нисходящая линия) текста. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Получает или задает строковое значение, которое используется в качестве штампа на странице. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Желаемая ширина штампа на странице. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Определяет перенос слов. Если для этого свойства установлено значение true и указано значение ширины, текст будет разбит на несколько строк, чтобы соответствовать указанной ширине. Значение по умолчанию:ложь. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Горизонтальная координата штампа, начиная слева. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Вертикальная координата штампа, начиная снизу. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет свойства ZoomX и ZoomY. Если ZoomX и ZoomY различны, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Коэффициент масштабирования штампа по горизонтали. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Коэффициент масштабирования штампа по вертикали. Позволяет масштабировать штамп по вертикали. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Возвращает идентификатор штампа. |
| override [Put](../../aspose.pdf/pagenumberstamp/put)(Page) | Добавляет номер страницы. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Устанавливает идентификатор штампа. |

### Смотрите также

* class [TextStamp](../textstamp)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
