---
title: Class SetAdvancedColor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.SetAdvancedColor. Класс, представляющий оператор scn установки цвета для нештриховых операций
type: docs
weight: 7560
url: /ru/net/aspose.pdf.operators/setadvancedcolor/
---
## Класс SetAdvancedColor

Класс, представляющий оператор scn (установка цвета для нештриховых операций).

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetAdvancedColor](setadvancedcolor/#constructor)() | Инициализирует оператор. |
| [SetAdvancedColor](setadvancedcolor/#constructor_1)(double) | Конструктор для оператора scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_6)(string) | Конструктор для оператора scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_4)(double, string) | Конструктор для оператора scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_5)(double[], string) | Конструктор для оператора scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_3)(double, double, double, string) | Конструктор для оператора scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_2)(double, double, double, double, string) | Конструктор для оператора scn. |

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Получает красный компонент цвета |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Получает циановый компонент цвета CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Получает массив компонентов цвета. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Получает зеленый компонент цвета |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Получает черный компонент серого цвета. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Получает черный компонент цвета CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Получает маджентовый компонент цвета CMYK. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Получает имя шаблона. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Получает красный компонент цвета |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Получает желтый компонент цвета CMYK. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolor/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolor/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* класс [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)