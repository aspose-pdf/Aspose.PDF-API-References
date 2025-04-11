---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.TextStateOperator. Абстрактный базовый класс для операторов, которые изменяют текущее состояние текста Tc Tf TL и т.д.
type: docs
weight: 7930
url: /ru/net/aspose.pdf.operators/textstateoperator/
---
## Класс TextStateOperator

Абстрактный базовый класс для операторов, которые изменяют текущее состояние текста (Tc, Tf, TL и т.д.).

```csharp
public class TextStateOperator : TextOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | Инициализирует TextStateOperator. |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | Инициализирует TextStateOperator, который позволяет передавать TextProperties. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с данным объектом. |

### См. также

* класс [TextOperator](../textoperator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)