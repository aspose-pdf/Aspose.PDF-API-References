---
title: Class SetCMYKColor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.SetCMYKColor. Класс, представляющий оператор k для установки цвета CMYK для нештриховых операций
type: docs
weight: 7580
url: /ru/net/aspose.pdf.operators/setcmykcolor/
---
## Класс SetCMYKColor

Класс, представляющий оператор k (устанавливает цвет CMYK для нештриховых операций).

```csharp
public class SetCMYKColor : SetColorOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetCMYKColor](setcmykcolor/)(double, double, double, double) | Инициализирует оператор. |

## Свойства

| Имя | Описание |
| --- | --- |
| [C](../../aspose.pdf.operators/setcmykcolor/c/) { get; set; } | Получает или задает компонент циан. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/setcmykcolor/k/) { get; set; } | Получает или задает компонент черного. |
| [M](../../aspose.pdf.operators/setcmykcolor/m/) { get; set; } | Получает или задает компонент маджента. |
| [Y](../../aspose.pdf.operators/setcmykcolor/y/) { get; set; } | Получает или задает компонент желтого. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcmykcolor/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [getColor](../../aspose.pdf.operators/setcmykcolor/getcolor/)() | Возвращает цвет. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с данным объектом. |

### См. также

* класс [SetColorOperator](../setcoloroperator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)