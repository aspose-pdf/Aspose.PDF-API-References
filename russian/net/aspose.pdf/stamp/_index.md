---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Stamp. Абстрактный класс для различных видов штампов, которые являются потомками
type: docs
weight: 10130
url: /ru/net/aspose.pdf/stamp/
---
## Класс Stamp

Абстрактный класс для различных видов штампов, которые являются потомками.

```csharp
public abstract class Stamp
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Устанавливает или получает значение типа bool, которое указывает, что содержимое штампа отображается как фон. Если значение истинно, содержимое штампа располагается внизу. По умолчанию значение ложно, содержимое штампа располагается сверху. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Получает или устанавливает нижний отступ штампа. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Желаемая высота штампа на странице. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Получает или устанавливает горизонтальное выравнивание штампа на странице. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Получает или устанавливает левый отступ штампа. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Получает или устанавливает значение, указывающее на непрозрачность штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Получает или устанавливает значение, указывающее на непрозрачность контура штампа. Значение от 0.0 до 1.0. По умолчанию значение 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Получает или устанавливает значение ширины контура штампа. По умолчанию значение 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Получает или устанавливает правый отступ штампа. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Устанавливает или получает вращение содержимого штампа в соответствии со значениями [`Rotation`](../rotation/). Примечание. Это свойство предназначено для установки углов, которые являются кратными 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, установленный с помощью ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None. |
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

| Имя | Описание |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Возвращает ID штампа. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Добавляет штамп на страницу. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Устанавливает ID штампа. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)