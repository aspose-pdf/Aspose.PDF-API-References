---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.SetColorStroke. Класс, представляющий оператор SC, устанавливающий цвет для операторов обводки
type: docs
weight: 7680
url: /ru/net/aspose.pdf.operators/setcolorstroke/
---
## Класс SetColorStroke

Класс, представляющий оператор SC, устанавливающий цвет для операторов обводки.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Инициализирует оператор. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Устанавливает цвет для операторов обводки для цветовых пространств DeviceGray, CalGray и Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Конструктор, который позволяет установить компоненты цвета. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Устанавливает цвет для оператора обводки для цветовых пространств DeviceRGB, CalRGB и Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Устанавливает цвет для оператора обводки для цветового пространства CMYK. |

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Получает или устанавливает синюю компоненту. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Получает или устанавливает циановую компоненту. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Получает массив компонентов цвета. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Получает или устанавливает зеленую компоненту. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Получает черную компоненту серого цвета. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Получает или устанавливает черную компоненту. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Получает или устанавливает пурпурную компоненту. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Получает или устанавливает красную компоненту. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Получает или устанавливает желтую компоненту. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* класс [BasicSetColorOperator](../basicsetcoloroperator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)