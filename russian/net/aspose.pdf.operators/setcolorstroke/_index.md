---
title: "Класс SetColorStroke"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Operators.SetColorStroke класс. Класс, представляющий оператор SC, устанавливающий цвет для операторов обводки"
type: docs
weight: 7820
url: /ru/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

Класс, представляющий оператор SC (устанавливает цвет для операторов обводки).

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Инициализирует оператор. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Установить цвет для операторов обводки для цветовых пространств DeviceGray, CalGray и Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Конструктор, позволяющий установить компоненты цвета. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Установить цвет для оператора обводки для цветовых пространств DeviceRGB, CalRGB и Lab |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Установить цвет для оператора обводки для цветового пространства CMYK |

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Получает или задает синий компонент. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Получает или задает циановый компонент. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Получает массив компонентов цвета. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Получает или задает зеленый компонент. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Получает чёрный компонент серого цвета. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Получает или задает черный компонент. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Получает или задает пурпурный компонент. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Получает или задает красный компонент. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Получает или задает желтый компонент. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Принимает объект‑посетитель для обработки оператора. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


