---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.TextShowOperator. Абстрактный базовый класс для всех операторов, которые используются для вывода текста Tj TJ и т.д.
type: docs
weight: 7920
url: /ru/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

Абстрактный базовый класс для всех операторов, которые используются для вывода текста (Tj, TJ и т.д.).

```csharp
public class TextShowOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Инициализирует TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Инициализирует TextShowOperator, который позволяет передавать TextProperties. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Получает текст, который оператор выводит на странице. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### See Also

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)