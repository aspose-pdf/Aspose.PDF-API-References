---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.TextStamp. Представляет текстовый штамп
type: docs
weight: 11080
url: /ru/net/aspose.pdf/textstamp/
---
## Класс TextStamp

Представляет текстовый штамп.

```csharp
public class TextStamp : Stamp
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | Инициализирует новый экземпляр класса `TextStamp` с объектом formattedText |
| [TextStamp](textstamp/#constructor_1)(string) | Инициализирует новый экземпляр класса `TextStamp`. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | Инициализирует новый экземпляр класса `TextStamp`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Автоматически настраивает точность размера шрифта. Значение по умолчанию: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Если включено, размер шрифта будет автоматически подстраиваться под прямоугольник штампа размером: [`Width`](./width/) и [`Height`](./height/). Значения ширины и высоты по умолчанию берутся из прямоугольника страницы. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает логическое значение, указывающее, что содержимое штампа является фоном. Если значение истинно, содержимое штампа располагается внизу. По умолчанию значение ложно, содержимое штампа располагается сверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или устанавливает нижний отступ штампа. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Это свойство определяет, как штамп рисуется на странице. Если Draw = true, штамп рисуется как графические операторы, а если draw = false, то штамп рисуется как текст. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Фактический размер шрифта после размещения штампа. (Может отличаться от начального размера шрифта, указанного через конструктор, если включена опция 'AutoAdjustFontSizeToFitStampRectangle'.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание штампа на странице. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Определяет выравнивание текста. Если это свойство установлено в true, то как левый, так и правый края текста выравниваются. Значение по умолчанию: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или устанавливает левый отступ штампа. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Максимальная высота строки для опции WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Получает или устанавливает режим, который определяет поведение в случае, если шрифты не содержат запрашиваемых символов. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или устанавливает значение, указывающее на непрозрачность штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или устанавливает значение, указывающее на непрозрачность контура штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или устанавливает значение ширины контура штампа. По умолчанию значение 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Получает или устанавливает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемого символа. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или устанавливает правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа в соответствии со значениями [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, которые являются кратными 90 градусам (0, 90, 180, 270 градусов). Чтобы установить произвольный угол, используйте свойство RotateAngle. Если угол, установленный свойством ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или устанавливает угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Определяет масштабирование текста. Если это свойство установлено в true и указано значение Width, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Выравнивание текста внутри штампа. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Получает свойства текста штампа. См. [`TextState`](./textstate/) для подробностей. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или устанавливает верхний отступ штампа. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Определяет координатное начало для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (линия спуска) текста. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Получает или устанавливает строковое значение, которое используется в качестве штампа на странице. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Желаемая ширина штампа на странице. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Получает или устанавливает режим переноса слов для рендеринга текста. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Горизонтальная координата штампа, начиная слева. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Вертикальная координата штампа, начиная снизу. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет как свойства ZoomX, так и ZoomY. Если ZoomX и ZoomY различны, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по вертикали. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает ID штампа. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | Добавляет текстовый штамп на страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает ID штампа. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | Действие, которое необходимо выполнить, если шрифт не содержит требуемого символа. |

### См. также

* класс [Stamp](../stamp/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)