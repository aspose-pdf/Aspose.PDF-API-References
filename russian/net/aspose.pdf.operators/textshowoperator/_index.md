---
title: "Класс TextShowOperator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Operators.TextShowOperator класс. Абстрактный базовый класс для всех операторов, используемых для вывода текста Tj, TJ и т.д."
type: docs
weight: 8060
url: /ru/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

Абстрактный базовый класс для всех операторов, используемых для вывода текста (Tj, TJ и др.).

```csharp
public class TextShowOperator : TextOperator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Инициализирует TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Инициализирует TextShowOperator, который позволяет передавать TextProperties. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Получает текст, который оператор выводит на страницу. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Принимает объект‑посетитель для обработки оператора. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Возвращает текст оператора и его параметры. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


