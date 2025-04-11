---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.SetColor. Представляет класс для оператора sc, устанавливающего цвет для неокрашивающих операций
type: docs
weight: 7630
url: /ru/net/aspose.pdf.operators/setcolor/
---
## Класс SetColor

Представляет класс для оператора sc (устанавливает цвет для неокрашивающих операций).

```csharp
public class SetColor : BasicSetColorOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Инициализирует оператор. |
| [SetColor](setcolor/#constructor_1)(double) | Устанавливает цвет для окрасочных операторов для цветовых пространств DeviceGray, CalGray и Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Конструктор, который позволяет указать компоненты цвета. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Устанавливает цвет для окрасочного оператора для цветовых пространств DeviceRGB, CalRGB и Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Устанавливает цвет для неокрашивающего оператора для цветового пространства CMYK. |

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Получает или устанавливает компонент синего цвета. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Получает или устанавливает компонент цианового цвета. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Получает массив компонентов цвета. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Получает или устанавливает компонент зеленого цвета. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Получает черный компонент серого цвета. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Получает или устанавливает черный компонент. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Получает или устанавливает компонент пурпурного цвета. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Получает или устанавливает компонент красного цвета. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Получает или устанавливает компонент желтого цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Возвращает строковое представление цвета. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* класс [BasicSetColorOperator](../basicsetcoloroperator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)