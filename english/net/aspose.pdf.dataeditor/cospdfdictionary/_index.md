---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.CosPdfDictionary class. A class for accessing an objects dictionary
type: docs
weight: 3530
url: /net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

A class for accessing an object's dictionary.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Constructors

| Name | Description |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Creates a dictionary from resources. |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Full collection of keys. Contains editable and not editable keys. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Gets the number of elements contained in the `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Gets a value indicating whether the `CosPdfDictionary` is read-only. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Gets or sets the element with the specified key. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Collection of editable keys. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Gets an ICollection containing the values in the `CosPdfDictionary`. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Creates an empty dictionary that will be attached to the document. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Creates an empty dictionary that will be attached to the page. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Set [`ICosPdfPrimitive`](../icospdfprimitive/) to dictionary. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Set [`ICosPdfPrimitive`](../icospdfprimitive/) to dictionary. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Removes all items from the `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determines whether the `CosPdfDictionary` contains a specific value. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Determines whether the `CosPdfDictionary` contains an element with the specified key. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Removes the first occurrence of a specific object from the `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Removes the element with the specified key from the `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Tries cast this instance to [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Tries cast this instance to `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Tries cast this instance to [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Tries cast this instance to [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Tries cast this instance to [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | For access to simple data type like string, name, bool, number. Returns null for other types. |

### See Also

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


