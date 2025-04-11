---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operator. Абстрактный класс, представляющий оператор
type: docs
weight: 7070
url: /ru/net/aspose.pdf/operator/
---
## Класс Оператор

Абстрактный класс, представляющий оператор.

```csharp
public abstract class Operator
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Принимает посетителя IOperatorSelector, который предоставляет обработку операторов. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с данным объектом. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Определяет, является ли оператор оператором, ответственным за вывод текста (Tj, TJ и т.д.) |

### См. Также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)