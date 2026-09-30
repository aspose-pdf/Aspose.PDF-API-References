---
title: "DictionaryEditor.TryGetValue"
linktitle: "TryGetValue"
articleTitle: "TryGetValue"
second_title: "Aspose.PDF for .NET API Reference"
description: "DictionaryEditor method. For access to simple data type like string, name, bool, number. Returns null for other types."
type: docs
weight: 60
url: "/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/"
product_version: "26.9.0"
---
## DictionaryEditor.TryGetValue method

For access to simple data type like string, name, bool, number.
 Returns null for other types.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | Key value |
| value | ICosPdfPrimitive& | returns <see cref="T:Aspose.Pdf.DataEditor.ICosPdfPrimitive" /> for key or null. |

### Return Value

Returns true if [`ICosPdfPrimitive`](../../../aspose.pdf.dataeditor/icospdfprimitive/) is like string, name, bool, number. 
 Returns false for all other types.

### See Also

* interface [ICosPdfPrimitive](../../../aspose.pdf.dataeditor/icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

