---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.AppearanceDictionary. Словарь внешнего вида аннотации, определяющий, как аннотация будет визуально представлена на странице
type: docs
weight: 1490
url: /ru/net/aspose.pdf.annotations/appearancedictionary/
---
## Класс AppearanceDictionary

Словарь внешнего вида аннотации, определяющий, как аннотация будет визуально представлена на странице.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Получает количество элементов, содержащихся в словаре. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Получает значение, указывающее, имеет ли словарь фиксированный размер. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Получает значение, указывающее, является ли словарь только для чтения. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к словарю (безопасно для потоков). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Представляет удобную форму для получения потоков внешнего вида. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Получает ключи словаря. Если словарь внешнего вида имеет подсловарь, то [`Keys`](./keys/) содержит значения (N&#x7C;R&#x7C;D).state, где N - нормальный внешний вид, R - внешний вид при наведении, D - внешний вид при нажатии, а state - имя состояния (например, Включено, Выключено для флажков). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к словарю. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Получает список значений словаря. Результирующая коллекция содержит список объектов XForm. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Добавляет пару с ключом и значением в словарь. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Добавляет X форму для указанного ключа. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Удаляет все элементы из словаря. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Проверяет, содержится ли указанная пара ключ-значение в словаре. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Копирует элементы словаря в массив, начиная с определенного индекса массива. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Возвращает объект IDictionaryEnumerator для словаря. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Удаляет пару ключ/значение из коллекции. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Удаляет ключ из словаря. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Пытается найти ключ в словаре и извлекает значение, если найдено. |

### См. также

* класс [XForm](../../aspose.pdf/xform/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)