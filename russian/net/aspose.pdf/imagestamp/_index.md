---
title: "Класс ImageStamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.ImageStamp. Представляет графическую печать"
type: docs
weight: 6060
url: /ru/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Представляет графическую печать.

```csharp
public sealed class ImageStamp : Stamp
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Инициализирует новый экземпляр класса `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Создаёт графическую печать из изображения в указанном файле. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Получает или задаёт альтернативный текст для графической печати. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает значение типа bool, указывающее, что содержимое наносится как фон. Если значение true, содержимое штампа размещается внизу. По умолчанию значение false, содержимое штампа размещается вверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или задаёт нижний отступ штампа. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Получает или задаёт высоту изображения. Установка этого параметра позволяет масштабировать изображение по вертикали. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание штампа на странице. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Получает поток изображения, используемый для печати. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или задаёт левый отступ штампа. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или задаёт значение, указывающее непрозрачность штампа. Значение находится в диапазоне от 0.0 до 1.0. По умолчанию значение равно 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или задаёт значение, указывающее непрозрачность контура штампа. Значение находится в диапазоне от 0.0 до 1.0. По умолчанию значение равно 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или задаёт значение ширины контура штампа. По умолчанию значение равно 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Получает или задаёт качество графической печати в процентах. Допустимые значения от 0 до 100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или задаёт правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа согласно значениям [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, кратных 90 градусам (0, 90, 180, 270 градусов). Чтобы установить произвольный угол, используйте свойство RotateAngle. Если угол, установленный через ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или задаёт угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или задаёт верхний отступ штампа. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или задаёт вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Получает или задаёт ширину изображения. Установка этого свойства позволяет масштабировать изображение по горизонтали. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Получает и задаёт горизонтальную координату печати, начиная с левого края. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Получает и задаёт вертикальную координату печати, начиная с нижнего края. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет задавать коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет оба свойства ZoomX и ZoomY. Если ZoomX и ZoomY различаются, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по вертикали. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает идентификатор штампа. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Добавляет графическую печать на страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает идентификатор штампа. |

### См. также

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


