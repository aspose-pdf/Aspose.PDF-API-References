---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.DictionaryEditor class. A class for accessing an documents tree dictionary document dictionary page dictionary resources dictionary
type: docs
weight: 3470
url: /net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class

A class for accessing an document's tree dictionary (document dictionary, page dictionary, resources dictionary).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Constructors

| Name | Description |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Full collection of keys. Contains editable and not editable keys. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Gets the number of elements contained in the `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Gets a value indicating whether the `DictionaryEditor` is read-only. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Gets or sets the element with the specified key. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Collection of editable keys. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Gets an ICollection containing the values in the `DictionaryEditor`. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Set [`ICosPdfPrimitive`](../icospdfprimitive/) to dictionary. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Set [`ICosPdfPrimitive`](../icospdfprimitive/) to dictionary. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Removes all items from the `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determines whether the `DictionaryEditor` contains a specific value. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Determines whether the `DictionaryEditor` contains an element with the specified key. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Removes the first occurrence of a specific object from the `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Removes the element with the specified key from the `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | For access to simple data type like string, name, bool, number. Returns null for other types. |

### See Also

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


