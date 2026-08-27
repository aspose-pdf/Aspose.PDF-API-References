---
title: "DictionaryEditor.TryGetValue"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод DictionaryEditor. Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов."
type: docs
weight: 150
url: /ru/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue method

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
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


