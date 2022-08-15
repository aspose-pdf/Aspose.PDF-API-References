---
title: TextStamp
second_title: Aspose.PDF для справочника API .NET
description: Повторно отображает текстовый штамп.
type: docs
weight: 7240
url: /ru/net/aspose.pdf/textstamp/
---
## TextStamp class

Повторно отображает текстовый штамп.

```csharp
public class TextStamp : Stamp
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextStamp](textstamp#constructor)(FormattedText) | Инициализирует новый экземпляр[`TextStamp`](../textstamp) класс с форматированным текстом object |
| [TextStamp](textstamp#constructor_1)(string) | Инициализирует новый экземпляр[`TextStamp`](../textstamp) класс. |
| [TextStamp](textstamp#constructor_2)(string, TextState) | Инициализирует новый экземпляр[`TextStamp`](../textstamp) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Устанавливает или получает логическое значение, указывающее, что содержимое штампуется как фон. Если значение равно true, содержимое штампа размещается внизу. По умолчанию значение равно false, содержимое штампа размещается вверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Получает или задает нижнее поле штампа. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Это свойство определяет способ отображения штампа на странице. Если Draw = true, штамп рисуется как графические операторы, а если draw = false, то штамп рисуется как текст. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание штампа на странице. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Определяет выравнивание текста. Если для этого свойства установлено значение true, выравниваются как левый, так и правый края текста. Значение по умолчанию: ложь. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Получает или задает левое поле штампа. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Максимальная высота строки для параметра WordWrap. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Получает или задает значение, указывающее непрозрачность штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Получает или задает значение, указывающее непрозрачность контура штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Получает или задает значение ширины контура штампа. По умолчанию значение равно 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Получает или задает правое поле штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Устанавливает или получает поворот содержимого штампа в соответствии с[`Rotation`](../rotation) значения. Примечание. Это свойство предназначено для установки углов, кратных 90 градусам (0, 90, 180, 270 градусов). Чтобы задать произвольный угол, используйте свойство RotateAngle. Если угол, установленный ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Получает или задает угол поворота штампа в градусах. Это свойство позволяет задать произвольный угол поворота. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Определяет масштабирование текста. Если для этого свойства установлено значение true и указано значение ширины, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Выравнивание текста внутри штампа. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Получает текстовые свойства штампа. Видеть[`TextState`](./textstate) подробнее. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Получает или задает верхнее поле штампа. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижнее ( линия спуска) текста. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Получает или задает строковое значение, которое используется в качестве штампа на странице. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Желаемая ширина штампа на странице. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Определяет перенос слов. Если для этого свойства установлено значение true и указано значение ширины, текст будет разбит на несколько строк, чтобы соответствовать указанной ширине. Значение по умолчанию: ложь. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Горизонтальная координата штампа, начиная слева. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Вертикальная координата штампа, начиная снизу. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет свойства ZoomX и ZoomY. Если ZoomX и ZoomY различаются, свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Коэффициент масштабирования штампа по горизонтали. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Коэффициент масштабирования штампа по вертикали. Позволяет масштабировать штамп по вертикали. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Возвращает идентификатор штампа. |
| override [Put](../../aspose.pdf/textstamp/put)(Page) | Добавляет текстовую печать на страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Устанавливает идентификатор штампа. |

### Смотрите также

* class [Stamp](../stamp)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
