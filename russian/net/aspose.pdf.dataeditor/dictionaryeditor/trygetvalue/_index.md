---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Метод DictionaryEditor. Для доступа к простым типам данных, таким как строка, имя, булевый, число. Возвращает null для других типов
type: docs
weight: 150
url: /ru/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## Метод DictionaryEditor.TryGetValue

Для доступа к простым типам данных, таким как строка, имя, булевый, число. Возвращает null для других типов.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | String | Значение ключа |
| value | ICosPdfPrimitive& | возвращает [`ICosPdfPrimitive`](../../icospdfprimitive/) для ключа или null. |

### Возвращаемое значение

Возвращает true, если [`ICosPdfPrimitive`](../../icospdfprimitive/) является строкой, именем, булевым значением, числом. Возвращает false для всех других типов.

### См. также

* интерфейс [ICosPdfPrimitive](../../icospdfprimitive/)
* класс [DictionaryEditor](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)