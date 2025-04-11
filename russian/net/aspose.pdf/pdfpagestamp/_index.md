---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PdfPageStamp. Класс представляет штамп, который использует страницу PDF в качестве штампа
type: docs
weight: 8420
url: /ru/net/aspose.pdf/pdfpagestamp/
---
## Класс PdfPageStamp

Класс представляет штамп, который использует страницу PDF в качестве штампа.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Конструктор PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Создает штамп страницы PDF из указанной страницы документа из потока. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Создает штамп страницы PDF из указанной страницы документа в указанном файле. |

## Свойства

| Название | Описание |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает логическое значение, указывающее, что содержимое штампа является фоном. Если значение истинно, содержимое штампа располагается внизу. По умолчанию значение ложно, содержимое штампа располагается сверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или устанавливает нижний отступ штампа. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание штампа на странице. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или устанавливает левый отступ штампа. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или устанавливает значение, указывающее непрозрачность штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или устанавливает значение, указывающее непрозрачность контура штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или устанавливает значение ширины контура штампа. По умолчанию значение 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Получает или устанавливает страницу, которая будет использоваться в качестве штампа. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или устанавливает правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа в соответствии со значениями [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, которые являются кратными 90 градусам (0, 90, 180, 270 градусов). Чтобы установить произвольный угол, используйте свойство RotateAngle. Если угол, установленный свойством ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Получает или устанавливает угол вращения штампа в градусах. Это свойство позволяет установить произвольный угол вращения. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Получает или устанавливает верхний отступ штампа. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание штампа на странице. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Желаемая ширина штампа на странице. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Горизонтальная координата штампа, начиная с левого края. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Вертикальная координата штампа, начиная с нижнего края. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет как свойства ZoomX, так и ZoomY. Если ZoomX и ZoomY различны, то свойство Zoom возвращает значение ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Вертикальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по вертикали. |

## Методы

| Название | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает ID штампа. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Помещает штамп на указанную страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает ID штампа. |

### См. также

* класс [Stamp](../stamp/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)