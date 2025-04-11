---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PageNumberStamp. Представляет штамп номера страницы и используется для нумерации страниц
type: docs
weight: 8230
url: /ru/net/aspose.pdf/pagenumberstamp/
---
## Класс PageNumberStamp

Представляет штамп номера страницы и используется для нумерации страниц.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Инициализирует новый экземпляр класса `PageNumberStamp`. Формат установлен на "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Создает PageNumberStamp по отформатированному тексту. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Инициализирует новый экземпляр класса `PageNumberStamp`. |

## Свойства

| Название | Описание |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Автоматически регулирует точность размера шрифта. Значение по умолчанию: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Если включено, размер шрифта будет автоматически подстраиваться под прямоугольник штампа размером: [`Width`](../textstamp/width/) и [`Height`](../textstamp/height/). Ширина и высота по умолчанию берутся из прямоугольника страницы. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает логическое значение, указывающее, что содержимое штампуется как фон. Если значение истинно, содержимое штампа располагается внизу. По умолчанию значение ложно, содержимое штампа располагается сверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или устанавливает нижний отступ штампа. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Это свойство определяет, как штамп рисуется на странице. Если Draw = true, штамп рисуется как графические операторы, а если draw = false, то штамп рисуется как текст. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Фактический размер шрифта после размещения штампа. (Может отличаться от начального размера шрифта, указанного через конструктор, если включена опция 'AutoAdjustFontSizeToFitStampRectangle'.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Строковое значение для штампования номеров страниц. Значение должно включать символ '#', который заменяется номером страницы в процессе штампования. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание штампа на странице. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Определяет выравнивание текста. Если это свойство установлено в true, оба края текста выравниваются. Значение по умолчанию: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или устанавливает левый отступ штампа. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Максимальная ширина строки для опции WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Получает или устанавливает режим, который определяет поведение в случае, если шрифты не содержат запрашиваемых символов. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Стиль нумерации, используемый этим штампом. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или устанавливает значение, указывающее на непрозрачность штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или устанавливает значение, указывающее на непрозрачность контура штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или устанавливает значение ширины контура штампа. По умолчанию значение 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Получает или устанавливает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемого символа. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или устанавливает правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа в соответствии со значениями [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, которые являются кратными 90 градусам (0, 90, 180, 270 градусов). Чтобы установить произвольный угол, используйте свойство RotateAngle. Если угол, установленный свойством ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или устанавливает угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Определяет масштабирование текста. Если это свойство установлено в true и указано значение Width, текст будет масштабироваться, чтобы соответствовать указанной ширине. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Получает или устанавливает значение номера начальной страницы. Другие страницы будут нумероваться, начиная с этого значения. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Выравнивание текста внутри штампа. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Получает свойства текста штампа. См. [`TextState`](../textstamp/textstate/) для получения подробной информации. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или устанавливает верхний отступ штампа. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Определяет координатное начало для размещения текста. Если TreatYIndentAsBaseLine = true (по умолчанию, когда Draw = true), значение YIndent будет рассматриваться как базовая линия текста. Если TreatYIndentAsBaseLine = false (по умолчанию, когда Draw = false), значение YIndent будет рассматриваться как нижняя (линия спуска) текста. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Получает или устанавливает строковое значение, которое используется как штамп на странице. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Желаемая ширина штампа на странице. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Получает или устанавливает режим переноса слов для рендеринга текста. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Горизонтальная координата штампа, начиная слева. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Вертикальная координата штампа, начиная снизу. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет как свойства ZoomX, так и ZoomY. Если ZoomX и ZoomY различны, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по вертикали. |

## Методы

| Название | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает ID штампа. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Добавляет номер страницы. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает ID штампа. |

### См. также

* класс [TextStamp](../textstamp/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)