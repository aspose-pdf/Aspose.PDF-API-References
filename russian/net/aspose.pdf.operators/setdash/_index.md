---
title: "Класс SetDash"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Operators.SetDash class. Класс, представляющий оператор d, задающий шаблон пунктирной линии"
type: docs
weight: 7830
url: /ru/net/aspose.pdf.operators/setdash/
---
## SetDash class

Класс, представляющий оператор d (устанавливает шаблон пунктирной линии).

```csharp
public class SetDash : Operator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Создаёт оператор установки шаблона пунктирной линии. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Индекс оператора в списке операторов страницы. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Шаблон пунктиров. Элементы массива должны быть числами, указывающими длину чередующихся тире и пробелов. В случае массива из одного элемента длина тире и пробела одинаковы. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Фаза пунктиров. Перед началом обводки пути массив пунктиров должен быть пройден, суммируя длины тире и пробелов. Когда накопленная длина достигает значения, указанного фазой пунктиров, обводка пути начинается, и массив пунктиров используется циклически с этого момента. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Принимает объект‑посетитель для обработки оператора. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Получает строковое представление оператора. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Сравнивает этот экземпляр с заданным объектом. |

### См. также

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


