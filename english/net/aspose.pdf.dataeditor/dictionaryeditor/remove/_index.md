---
title: "DictionaryEditor.Remove"
linktitle: "Remove"
articleTitle: "Remove"
second_title: "Aspose.PDF for .NET API Reference"
description: "DictionaryEditor method. Removes the element with the specified key from the DictionaryEditor."
type: docs
weight: 50
url: "/net/aspose.pdf.dataeditor/dictionaryeditor/remove/"
product_version: "26.9.0"
---
## Remove(KeyValuePair<string, ICosPdfPrimitive>) {#remove}

Removes the first occurrence of a specific object from the [`DictionaryEditor`](../../../aspose.pdf.dataeditor/dictionaryeditor/).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | The object to remove from the <see cref="T:Aspose.Pdf.DataEditor.DictionaryEditor" />. |

### Return Value

true if item was successfully removed from the [`DictionaryEditor`](../../../aspose.pdf.dataeditor/dictionaryeditor/);
 otherwise, false. This method also returns false if item is not found in the
 original [`DictionaryEditor`](../../../aspose.pdf.dataeditor/dictionaryeditor/).

### See Also

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Removes the element with the specified key from the [`DictionaryEditor`](../../../aspose.pdf.dataeditor/dictionaryeditor/).

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | The key of the element to remove. |

### Return Value

True if the element is successfully removed; otherwise, false. 
 This method also returns false if key was not found in the original dictionary or key the key is not editable

### See Also

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

