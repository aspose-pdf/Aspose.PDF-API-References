---
title: Class BasicSetColorOperator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.BasicSetColorOperator. Базовый класс для операторов установки цвета
type: docs
weight: 7160
url: /ru/net/aspose.pdf.operators/basicsetcoloroperator/
---
## Класс BasicSetColorOperator

Базовый класс для операторов установки цвета.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

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
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Получает красный компонент цвета |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Получает желтый компонент цвета CMYK. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Принимает посетителя IOperatorSelector, который предоставляет обработку операторов. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* класс [SetColorOperator](../setcoloroperator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)