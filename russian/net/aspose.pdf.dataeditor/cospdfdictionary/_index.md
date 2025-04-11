---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.DataEditor.CosPdfDictionary. Класс для доступа к словарю объектов
type: docs
weight: 3420
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## Класс CosPdfDictionary

Класс для доступа к словарю объекта.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Создает словарь из ресурсов. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Полная коллекция ключей. Содержит редактируемые и нерегируемые ключи. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Получает количество элементов, содержащихся в `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Получает значение, указывающее, является ли `CosPdfDictionary` только для чтения. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Получает или устанавливает элемент с указанным ключом. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Коллекция редактируемых ключей. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Получает ICollection, содержащий значения в `CosPdfDictionary`. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Создает пустой словарь, который будет прикреплен к документу. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Создает пустой словарь, который будет прикреплен к странице. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Устанавливает [`ICosPdfPrimitive`](../icospdfprimitive/) в словарь. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Устанавливает [`ICosPdfPrimitive`](../icospdfprimitive/) в словарь. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Удаляет все элементы из `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Определяет, содержит ли `CosPdfDictionary` конкретное значение. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Определяет, содержит ли `CosPdfDictionary` элемент с указанным ключом. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Возвращает перечислитель, который перебирает коллекцию. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Удаляет первое вхождение конкретного объекта из `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Удаляет элемент с указанным ключом из `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Пытается привести этот экземпляр к [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Пытается привести этот экземпляр к `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Пытается привести этот экземпляр к [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Пытается привести этот экземпляр к [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Пытается привести этот экземпляр к [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Для доступа к простым типам данных, таким как строка, имя, булево значение, число. Возвращает null для других типов. |

### См. также

* класс [CosPdfPrimitive](../cospdfprimitive/)
* интерфейс [ICosPdfPrimitive](../icospdfprimitive/)
* пространство имен [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../)