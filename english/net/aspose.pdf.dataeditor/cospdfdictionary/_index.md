---
title: "CosPdfDictionary Class"
linktitle: "CosPdfDictionary"
articleTitle: "CosPdfDictionary"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.DataEditor.CosPdfDictionary class. A class for accessing an object's dictionary."
type: docs
weight: 30
url: "/net/aspose.pdf.dataeditor/cospdfdictionary/"
keywords: "CosPdfDictionary, Aspose.Pdf.DataEditor, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CosPdfDictionary class

A class for accessing an object's dictionary.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Constructors

| Name | Description |
| --- | --- |
| [CosPdfDictionary](./cospdfdictionary/)(Resources) | Creates a dictionary from resources. |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](./allkeys/) { get; } | Full collection of keys. Contains editable and not editable keys. |
| [Count](./count/) { get; } | Gets the number of elements contained in the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/). |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/) is read-only. |
| [Item](./item/) { get; set; } | Gets or sets the element with the specified key. |
| [Keys](./keys/) { get; } | Collection of editable keys. |
| [Values](./values/) { get; } | Gets an `ICollection` containing the values in the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/). |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(KeyValuePair<string, ICosPdfPrimitive>) | Set [`ICosPdfPrimitive`](../../aspose.pdf.dataeditor/icospdfprimitive/) to dictionary. |
| [Add](./add/)(string, ICosPdfPrimitive) | Set [`ICosPdfPrimitive`](../../aspose.pdf.dataeditor/icospdfprimitive/) to dictionary. |
| [Clear](./clear/)() | Removes all items from the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/). |
| [Contains](./contains/)(KeyValuePair<string, ICosPdfPrimitive>) | Determines whether the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/) contains a specific value. |
| [ContainsKey](./containskey/)(string) | Determines whether the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/) contains an element with the specified key. |
| [CopyTo](./copyto/)(KeyValuePair<string, ICosPdfPrimitive>[], int) |  |
| static [CreateEmptyDictionary](./createemptydictionary/)(Document) | Creates an empty dictionary that will be attached to the document. |
| static [CreateEmptyDictionary](./createemptydictionary/)(Page) | Creates an empty dictionary that will be attached to the page. |
| [GetEnumerator](./getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [Remove](./remove/)(KeyValuePair<string, ICosPdfPrimitive>) | Removes the first occurrence of a specific object from the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/). |
| [Remove](./remove/)(string) | Removes the element with the specified key from the [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/). |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Tries cast this instance to [`CosPdfBoolean`](../../aspose.pdf.dataeditor/cospdfboolean/). |
| override [ToCosPdfDictionary](./tocospdfdictionary/)() | Tries cast this instance to [`CosPdfDictionary`](../../aspose.pdf.dataeditor/cospdfdictionary/). |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Tries cast this instance to [`CosPdfName`](../../aspose.pdf.dataeditor/cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Tries cast this instance to [`CosPdfNumber`](../../aspose.pdf.dataeditor/cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Tries cast this instance to [`CosPdfString`](../../aspose.pdf.dataeditor/cospdfstring/). |
| [ToString](../../aspose.pdf.dataeditor/icospdfprimitive/tostring/)() | `String` representation of instance [`ICosPdfPrimitive`](../../aspose.pdf.dataeditor/icospdfprimitive/). |
| [TryGetValue](./trygetvalue/)(string, out ICosPdfPrimitive) | For access to simple data type like string, name, bool, number. Returns null for other types. |

### See Also

* class [CosPdfPrimitive](../cospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)

