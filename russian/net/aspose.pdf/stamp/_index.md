---
title: "Класс Stamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Stamp class. Абстрактный класс для различных видов штампов, которые являются наследниками."
type: docs
weight: 10310
url: /ru/net/aspose.pdf/stamp/
---
## Stamp class

Абстрактный класс для различных видов штампов, которые являются наследниками.

```csharp
public abstract class Stamp
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает значение типа bool, указывающее, что содержимое наносится как фон. Если значение true, содержимое штампа размещается внизу. По умолчанию значение false, содержимое штампа размещается вверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или задаёт нижний отступ штампа. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание штампа на странице. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или задаёт левый отступ штампа. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или задаёт значение, указывающее непрозрачность штампа. Значение находится в диапазоне от 0.0 до 1.0. По умолчанию значение равно 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или задаёт значение, указывающее непрозрачность контура штампа. Значение находится в диапазоне от 0.0 до 1.0. По умолчанию значение равно 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или задаёт значение ширины контура штампа. По умолчанию значение равно 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или задаёт правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа согласно значениям [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, кратных 90 градусам (0, 90, 180, 270 градусов). Чтобы установить произвольный угол, используйте свойство RotateAngle. Если угол, установленный через ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или задаёт угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или задаёт верхний отступ штампа. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или задаёт вертикальное выравнивание штампа на странице. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Желаемая ширина штампа на странице. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Горизонтальная координата штампа, начиная с левого края. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Вертикальная координата штампа, отсчитываемая от низа. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет задавать коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет оба свойства ZoomX и ZoomY. Если ZoomX и ZoomY различаются, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по вертикали. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает идентификатор штампа. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Добавляет штамп на страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает идентификатор штампа. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


