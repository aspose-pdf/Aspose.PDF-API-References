---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary class. Annotation appearance dictionary specifying how the annotation shall be presented visually on the page
type: docs
weight: 1490
url: /net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Gets the number of elements contained in the dictionary. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Gets a value indicating whether dictionary has a fixed size. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Gets a value indicating whether dictionary is read-only. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Gets a value indicating whether access to the dictionary is synchronized (thread safe). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Represents convenient form for getting appearance streams. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [`Keys`](./keys/) contains (N&#x7C;R&#x7C;D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Gets an object that can be used to synchronize access to the dictionary. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Gets the list of the dictionary values. Result collection contains the list of XForm objects. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Adds pair with key and value into the dictionary. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Add X form for specifed key. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Removes all elements from the dictionary. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Checks does specified key-value pair is contained in the dictionary. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Determines does this dictionary contasins specified key. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Copies the elements of the dictionary to an Array, starting at a particular Array index. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Returns an IDictionaryEnumerator object for the dictionary. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Removes key/value pair from the collection. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Removes key from the dictionary. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Tries to find key in the dictionary and retreives value if found. |

### See Also

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


