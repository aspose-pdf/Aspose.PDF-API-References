---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Utils.DictionaryEditor class. A class for accessing an objects dictionary
type: docs
weight: 8740
url: /net/aspose.pdf.utils/dictionaryeditor/
---
## DictionaryEditor class

A class for accessing an object's dictionary.

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Constructors

| Name | Description |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.utils/dictionaryeditor/allkeys/) { get; } | Full collection of keys. Contains editable and not editable keys. |
| [Count](../../aspose.pdf.utils/dictionaryeditor/count/) { get; } | Gets the number of elements contained in the `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.utils/dictionaryeditor/isreadonly/) { get; } | Gets a value indicating whether the `DictionaryEditor` is read-only. |
| [Item](../../aspose.pdf.utils/dictionaryeditor/item/) { get; set; } | Gets or sets the element with the specified key. |
| [Keys](../../aspose.pdf.utils/dictionaryeditor/keys/) { get; } | Collection of editable keys. |
| [Values](../../aspose.pdf.utils/dictionaryeditor/values/) { get; } | Gets an ICollection containing the values in the `DictionaryEditor`. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.utils/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Set [`ICosPdfPrimitive`](../../aspose.pdf.utils.publicdata/icospdfprimitive/) to dictionary. |
| [Add](../../aspose.pdf.utils/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Set [`ICosPdfPrimitive`](../../aspose.pdf.utils.publicdata/icospdfprimitive/) to dictionary. |
| [Clear](../../aspose.pdf.utils/dictionaryeditor/clear/)() | Removes all items from the `DictionaryEditor`. |
| [Contains](../../aspose.pdf.utils/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determines whether the `DictionaryEditor` contains a specific value. |
| [ContainsKey](../../aspose.pdf.utils/dictionaryeditor/containskey/)(string) | Determines whether the `DictionaryEditor` contains an element with the specified key. |
| [CopyTo](../../aspose.pdf.utils/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.utils/dictionaryeditor/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../aspose.pdf.utils/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Removes the first occurrence of a specific object from the `DictionaryEditor`. |
| [Remove](../../aspose.pdf.utils/dictionaryeditor/remove/#remove_1)(string) | Removes the element with the specified key from the `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.utils/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | For access to simple data type like string, name, bool, number. Returns null for other types. |

### See Also

* interface [ICosPdfPrimitive](../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* namespace [Aspose.Pdf.Utils](../../aspose.pdf.utils/)
* assembly [Aspose.PDF](../../)


