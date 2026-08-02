---
title: "CosPdfDictionary.Item"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство CosPdfDictionary. Получает или задаёт элемент с указанным ключом."
type: docs
weight: 60
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary indexer

Получает или задает элемент с указанным ключом.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| ключ | Ключ элемента, который нужно получить или задать. |

### Возвращаемое значение

Элемент с указанным ключом.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Ключ равен null. |
| KeyNotFoundException | Свойство получено, но ключ не найден. |
| ArgumentException | Выбросить исключение, если ключ нельзя изменить/установить. |

### См. также

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


