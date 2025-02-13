---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary method. For access to simple data type like string name bool number. Returns null for other types
type: docs
weight: 170
url: /net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue method

For access to simple data type like string, name, bool, number. Returns null for other types.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key value |
| value | ICosPdfPrimitive& | returns [`ICosPdfPrimitive`](../../icospdfprimitive/) for key or null. |

### Return Value

Returns true if [`ICosPdfPrimitive`](../../icospdfprimitive/) is like string, name, bool, number. Returns false for all other types.

### See Also

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


