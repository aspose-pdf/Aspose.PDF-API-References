---
title: Class TextOperator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.TextOperator. Абстрактный базовый класс для операторов, связанных с текстом TJ Tj Tm BT ET и т.д.
type: docs
weight: 7900
url: /ru/net/aspose.pdf.operators/textoperator/
---
## Класс TextOperator

Абстрактный базовый класс для операторов, связанных с текстом (TJ, Tj, Tm, BT, ET и т.д.).

```csharp
public abstract class TextOperator : Operator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextOperator](textoperator/#constructor)() | Инициализирует оператор. |
| [TextOperator](textoperator/#constructor_1)(TextProperties) | Оператор текста, который принимает свойства текста. |

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

* класс [Operator](../../aspose.pdf/operator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)