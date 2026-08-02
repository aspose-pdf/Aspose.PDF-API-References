---
title: "Класс SetColor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Operators.SetColor class. Представляет класс для оператора sc, устанавливающего цвет для операций без обводки"
type: docs
weight: 7770
url: /ru/net/aspose.pdf.operators/setcolor/
---
## SetColor class

Представляет класс для оператора sc (устанавливает цвет для операций без обводки).

```csharp
public class SetColor : BasicSetColorOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Инициализирует оператор. |
| [SetColor](setcolor/#constructor_1)(double) | Установить цвет для операторов обводки для цветовых пространств DeviceGray, CalGray и Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Конструктор, позволяющий задавать компоненты цвета. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Установить цвет для оператора обводки для цветовых пространств DeviceRGB, CalRGB и Lab |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Устанавливает цвет для оператора без обводки в цветовом пространстве CMYK |

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Получает или задает синий компонент. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Получает или задает циановый компонент. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Получает массив компонентов цвета. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Получает или задает зеленый компонент. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Получает чёрный компонент серого цвета. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Получает или задает черный компонент. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Получает или задает пурпурный компонент. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Получает или задает красный компонент. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Получает или задает желтый компонент. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Принимает объект‑посетитель для обработки оператора. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Возвращает строковое представление цвета. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


