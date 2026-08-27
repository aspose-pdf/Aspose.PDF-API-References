---
title: "Класс PageNumberStamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.PageNumberStamp. Представляет штамп номера страницы и используется для нумерации страниц."
type: docs
weight: 8370
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
| [PageNumberStamp](pagenumberstamp/#constructor)() | Инициализирует новый экземпляр класса `PageNumberStamp`. Формат установлен в "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Создаёт PageNumberStamp с помощью отформатированного текста. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Инициализирует новый экземпляр класса `PageNumberStamp`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Автоматически корректировать точность размера шрифта. Значение по умолчанию: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Если включено, размер шрифта будет автоматически подгоняться под прямоугольник штампа размера: [`Width`](../textstamp/width/) и [`Height`](../textstamp/height/). Ширина и высота по умолчанию берутся из прямоугольника страницы. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает значение типа bool, указывающее, что содержимое наносится как фон. Если значение true, содержимое штампа размещается внизу. По умолчанию значение false, содержимое штампа размещается вверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или задаёт нижний отступ штампа. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Это свойство определяет, как печать рисуется на странице. Если Draw = true, печать рисуется как графические операторы, а если draw = false, то печать рисуется как текст. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Фактический размер шрифта после размещения печати. (Может отличаться от начального размера шрифта, указанного в конструкторе, если включена опция 'AutoAdjustFontSizeToFitStampRectangle'.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Строковое значение для штамповки номеров страниц. Значение должно содержать символ '#', который заменяется номером страницы в процессе штамповки. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание штампа на странице. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Определяет выравнивание текста. Если это свойство установлено в true, обе границы текста (левая и правая) выравниваются. Значение по умолчанию: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или задаёт левый отступ штампа. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Максимальная высота строки для опции WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Получает или задает режим, определяющий поведение в случае, если шрифты не содержат требуемые символы. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Стиль нумерации, используемый этим штампом. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или задаёт значение, указывающее непрозрачность штампа. Значение находится в диапазоне от 0.0 до 1.0. По умолчанию значение равно 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или задаёт значение, указывающее непрозрачность контура штампа. Значение находится в диапазоне от 0.0 до 1.0. По умолчанию значение равно 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или задаёт значение ширины контура штампа. По умолчанию значение равно 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемый символ. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или задаёт правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа согласно значениям [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, кратных 90 градусам (0, 90, 180, 270 градусов). Чтобы установить произвольный угол, используйте свойство RotateAngle. Если угол, установленный через ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или задаёт угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Определяет масштабирование текста. Если это свойство установлено в true и указано значение Width, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Получает или задаёт значение номера начальной страницы. Последующие страницы будут нумероваться, начиная с этого значения. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Выравнивание текста внутри печати. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Получает свойства текста штампа. См. [`TextState`](../textstamp/textstate/) для подробностей. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или задаёт верхний отступ штампа. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Определяет начало координат для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (линия спуска) текста. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Получает или задает строковое значение, используемое в качестве штампа на странице. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или задаёт вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Желаемая ширина штампа на странице. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Получает или задает режим переноса слов при отображении текста. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Горизонтальная координата штампа, начиная с левого края. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Вертикальная координата штампа, отсчитываемая от низа. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет задавать коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет оба свойства ZoomX и ZoomY. Если ZoomX и ZoomY различаются, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по вертикали. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает идентификатор штампа. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Добавляет номер страницы. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает идентификатор штампа. |

### См. также

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


