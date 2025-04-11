---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Operators.SetDash. Класс, представляющий оператор d, устанавливающий шаблон штриха линии
type: docs
weight: 7690
url: /ru/net/aspose.pdf.operators/setdash/
---
## Класс SetDash

Класс, представляющий оператор d (устанавливающий шаблон штриха линии).

```csharp
public class SetDash : Operator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Создает оператор шаблона штриха. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Шаблон штриха. Элементы массива должны быть числами, которые указывают длины чередующихся штрихов и пробелов. В случае массива с одним элементом длины штриха и пробела равны. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Фаза штриха. Перед началом обводки пути массив штрихов должен быть циклически обработан, суммируя длины штрихов и пробелов. Когда накопленная длина равна значению, указанному фазой штриха, начинается обводка пути, и массив штрихов будет использоваться циклически с этого момента. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Принимает объект посетителя для обработки оператора. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Получает строковое представление оператора. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с данным объектом. |

### См. также

* класс [Operator](../../aspose.pdf/operator/)
* пространство имен [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* сборка [Aspose.PDF](../../)