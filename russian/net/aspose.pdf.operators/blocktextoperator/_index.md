---
title: Class BlockTextOperator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.BlockTextOperator. Абстрактный базовый класс для операторов текстовых блоков, т.е. операторов начала и конца текста BT/ET
type: docs
weight: 7170
url: /ru/net/aspose.pdf.operators/blocktextoperator/
---
## Класс BlockTextOperator

Абстрактный базовый класс для операторов текстовых блоков, т.е. операторов начала и конца текста (BT/ET)

```csharp
public class BlockTextOperator : TextOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BlockTextOperator](blocktextoperator/#constructor)() | Инициализирует оператор. |
| [BlockTextOperator](blocktextoperator/#constructor_1)(TextProperties) | Инициализирует BlockTextOperator, который принимает TextProperties. |

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