---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.ImageStamp. Представляет графический штамп
type: docs
weight: 5930
url: /ru/net/aspose.pdf/imagestamp/
---
## Класс ImageStamp

Представляет графический штамп.

```csharp
public sealed class ImageStamp : Stamp
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Инициализирует новый экземпляр класса `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Создает изображение штампа по изображению в указанном файле. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Получает или задает альтернативный текст для изображения штампа. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает логическое значение, указывающее, что содержимое штампа используется как фон. Если значение истинно, содержимое штампа располагается внизу. По умолчанию значение ложно, содержимое штампа располагается сверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или задает нижний отступ штампа. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Получает или задает высоту изображения. Установка этого изображения позволяет масштабировать изображение вертикально. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание штампа на странице. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Получает поток изображения, используемый для штамповки. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или задает левый отступ штампа. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или задает значение, указывающее непрозрачность штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или задает значение, указывающее непрозрачность контура штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или задает значение ширины контура штампа. По умолчанию значение 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Получает или задает качество изображения штампа в процентах. Допустимые значения от 0 до 100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или задает правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа в соответствии со значениями [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, которые являются кратными 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, установленный свойством ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или задает угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или задает верхний отступ штампа. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание штампа на странице. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Получает или задает ширину изображения. Установка этого свойства позволяет масштабировать изображение горизонтально. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Получает и задает горизонтальную координату штампа, начиная слева. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Получает и задает вертикальную координату штампа, начиная снизу. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет как свойства ZoomX, так и ZoomY. Если ZoomX и ZoomY различны, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп горизонтально. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп вертикально. |

## Методы

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает ID штампа. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Добавляет графический штамп на страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает ID штампа. |

### См. также

* класс [Stamp](../stamp/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)