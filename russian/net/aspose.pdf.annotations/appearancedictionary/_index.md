---
title: "Класс AppearanceDictionary"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Annotations.AppearanceDictionary. Словарь внешнего вида аннотации, определяющий, как аннотация будет визуально представлена на странице."
type: docs
weight: 1580
url: /ru/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

Словарь внешнего вида аннотации, указывающий, как аннотация должна визуально отображаться на странице.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Получает количество элементов, содержащихся в словаре. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Получает значение, указывающее, имеет ли словарь фиксированный размер. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Получает значение, указывающее, является ли словарь только для чтения. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к словарю (потокобезопасный). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Представляет удобную форму для получения потоков внешнего вида. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Получает ключи словаря. Если словарь внешнего вида имеет подсловаря, то [`Keys`](./keys/) содержит значения (N&#x7C;R&#x7C;D).state, где N — обычный внешний вид, R — внешний вид при наведении, D — внешний вид при нажатии, а state — имя состояния (например, On, Off для флажков). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Получает объект, который может использоваться для синхронизации доступа к словарю. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Получает список значений словаря. Коллекция результата содержит список объектов XForm. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Добавляет пару ключ‑значение в словарь. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Добавить X‑форму для указанного ключа. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Удаляет все элементы из словаря. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Проверяет, содержится ли указанная пара ключ‑значение в словаре. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Копирует элементы словаря в массив, начиная с определённого индекса массива. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Возвращает объект IDictionaryEnumerator для словаря. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Удаляет пару ключ/значение из коллекции. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Удаляет ключ из словаря. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Пытается найти ключ в словаре и получает значение, если найдено. |

### См. также

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


