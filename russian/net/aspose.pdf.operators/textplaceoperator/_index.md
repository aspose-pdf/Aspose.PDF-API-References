---
title: Class TextPlaceOperator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.TextPlaceOperator. Абстрактный базовый класс для операторов, которые изменяют положение текста Tm Td и т.д.
type: docs
weight: 7910
url: /ru/net/aspose.pdf.operators/textplaceoperator/
---
## TextPlaceOperator class

Абстрактный базовый класс для операторов, которые изменяют положение текста (Tm, Td и т.д.).

```csharp
public class TextPlaceOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextPlaceOperator](textplaceoperator/#constructor)() | Инициализирует TextPlaceOperator. |
| [TextPlaceOperator](textplaceoperator/#constructor_1)(TextProperties) | Инициализирует TextPlaceOperator, который принимает TextProperties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с данным объектом. |

### See Also

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)