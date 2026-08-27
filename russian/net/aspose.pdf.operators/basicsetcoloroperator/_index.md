---
title: "Класс BasicSetColorOperator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Operators.BasicSetColorOperator класс. Базовый класс для операторов установки цвета"
type: docs
weight: 7300
url: /ru/net/aspose.pdf.operators/basicsetcoloroperator/
---
## BasicSetColorOperator class

Базовый класс для операторов установки цвета.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## Свойства

| Имя | Описание |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Получает красный компонент цвета |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Получает компонент циана цвета CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Получает массив компонентов цвета. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Получает зелёный компонент цвета |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Получает чёрный компонент серого цвета. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Получает чёрный компонент цвета CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Получает пурпурный (магента) компонент цвета CMYK. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Получает красный компонент цвета |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Получает жёлтый компонент цвета CMYK. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Принимает посетитель IOperatorSelector, который обеспечивает обработку операторов. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Возвращает цвет, указанный оператором. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


