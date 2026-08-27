---
title: "Класс BasicSetColorAndPatternOperator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Operators.BasicSetColorAndPatternOperator класс. Базовый оператор для всех операторов Set Color"
type: docs
weight: 7290
url: /ru/net/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## BasicSetColorAndPatternOperator class

Базовый оператор для всех операторов установки цвета.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
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
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Получает имя шаблона. |
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

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


