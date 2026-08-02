---
title: "CosPdfDictionary.TryGetValue"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод CosPdfDictionary. Для доступа к простым типам данных, таким как строка, имя, bool, число. Возвращает null для других типов."
type: docs
weight: 170
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue method

Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | String | Значение ключа |
| value | ICosPdfPrimitive& | возвращает [`ICosPdfPrimitive`](../../icospdfprimitive/) для ключа или null. |

### Возвращаемое значение

Возвращает true, если [`ICosPdfPrimitive`](../../icospdfprimitive/) похож на string, name, bool, number. Возвращает false для всех остальных типов.

### См. также

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


