---
title: "DictionaryEditor Class"
linktitle: "DictionaryEditor"
articleTitle: "DictionaryEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.DataEditor.DictionaryEditor class. A class for accessing an document's tree dictionary (document dictionary, page dictionary, resources dictionary)."
type: docs
weight: 80
url: "/net/aspose.pdf.dataeditor/dictionaryeditor/"
keywords: "DictionaryEditor, Aspose.Pdf.DataEditor, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DictionaryEditor class

A class for accessing an document's tree dictionary (document dictionary, page dictionary, resources dictionary).

```csharp
public class DictionaryEditor : IEnumerable
```

## Constructors

| Name | Description |
| --- | --- |
| [DictionaryEditor](./dictionaryeditor/#constructor)(*[Page](../../aspose.pdf/page/)*) | Initializes a new instance of the DictionaryEditor class. |
| [DictionaryEditor](./dictionaryeditor/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes a new instance of the DictionaryEditor class. |
| [DictionaryEditor](./dictionaryeditor/#constructor_2)(*[Resources](../../aspose.pdf/resources/)*) | Initializes a new instance of the DictionaryEditor class. |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](./allkeys/) { get; } | Full collection of keys. |
| [Count](./count/) { get; } | Gets the number of elements contained in the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/). |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/) is read-only. |
| [Item](./item/) { get; set; } |  |
| [Keys](./keys/) { get; } | Collection of editable keys. |
| [Values](./values/) { get; } | Gets an `ICollection` containing the values in the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/). |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*KeyValuePair<string, ICosPdfPrimitive>*) | Set [`ICosPdfPrimitive`](../../aspose.pdf.dataeditor/icospdfprimitive/) to dictionary. |
| [Add](./add/)(*string, ICosPdfPrimitive*) | Set [`ICosPdfPrimitive`](../../aspose.pdf.dataeditor/icospdfprimitive/) to dictionary. |
| [Clear](./clear/) | Removes all items from the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/). |
| [Contains](./contains/)(*KeyValuePair<string, ICosPdfPrimitive>*) | Determines whether the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/) contains a specific value. |
| [ContainsKey](./containskey/)(*string*) | Determines whether the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/) contains an element with the specified key. |
| [CopyTo](./copyto/)(*KeyValuePair<string, ICosPdfPrimitive>[], int*) |  |
| [GetEnumerator](./getenumerator/) | Returns an enumerator that iterates through the collection. |
| [Remove](./remove/)(*string*) | Removes the element with the specified key from the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/). |
| [Remove](./remove/)(*KeyValuePair<string, ICosPdfPrimitive>*) | Removes the first occurrence of a specific object from the [`DictionaryEditor`](../../aspose.pdf.dataeditor/dictionaryeditor/). |
| [TryGetValue](./trygetvalue/)(*string, ICosPdfPrimitive*) |  |

### See Also

* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)

