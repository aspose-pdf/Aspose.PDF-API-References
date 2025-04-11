---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: Свойство CosPdfDictionary. Получает или устанавливает элемент с указанным ключом
type: docs
weight: 60
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## Индексатор CosPdfDictionary

Получает или устанавливает элемент с указанным ключом.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| key | Ключ элемента, который нужно получить или установить. |

### Возвращаемое значение

Элемент с указанным ключом.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Ключ равен null. |
| KeyNotFoundException | Свойство извлекается, и ключ не найден. |
| ArgumentException | Выбрасывает исключение, если ключ не может быть отредактирован/установлен. |

### См. также

* интерфейс [ICosPdfPrimitive](../../icospdfprimitive/)
* класс [CosPdfDictionary](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)