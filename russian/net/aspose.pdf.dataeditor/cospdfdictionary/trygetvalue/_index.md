---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Метод CosPdfDictionary. Для доступа к простым типам данных, таким как строка, имя, булевый, число. Возвращает null для других типов
type: docs
weight: 170
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## Метод CosPdfDictionary.TryGetValue

Для доступа к простым типам данных, таким как строка, имя, булевый, число. Возвращает null для других типов.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | String | Значение ключа |
| value | ICosPdfPrimitive& | возвращает [`ICosPdfPrimitive`](../../icospdfprimitive/) для ключа или null. |

### Возвращаемое значение

Возвращает true, если [`ICosPdfPrimitive`](../../icospdfprimitive/) является строкой, именем, булевым, числом. Возвращает false для всех других типов.

### См. также

* интерфейс [ICosPdfPrimitive](../../icospdfprimitive/)
* класс [CosPdfDictionary](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)