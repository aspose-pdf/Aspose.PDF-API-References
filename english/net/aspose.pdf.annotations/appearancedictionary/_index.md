---
title: "AppearanceDictionary Class"
linktitle: "AppearanceDictionary"
articleTitle: "AppearanceDictionary"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.AppearanceDictionary class. Annotation appearance dictionary specifying how the annotation shall be presented visually on the page."
type: docs
weight: 110
url: "/net/aspose.pdf.annotations/appearancedictionary/"
keywords: "AppearanceDictionary, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AppearanceDictionary class

[Annotation](../annotation/) appearance dictionary specifying how the annotation shall be presented visually on the page.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets the number of elements contained in the dictionary. |
| [IsFixedSize](./isfixedsize/) { get; } | Gets a value indicating whether dictionary has a fixed size. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether dictionary is read-only. |
| [IsSynchronized](./issynchronized/) { get; } | Gets a value indicating whether access to the dictionary is synchronized (thread safe). |
| [Item](./item/) { get; set; } | Represents convenient form for getting appearance streams. |
| [Keys](./keys/) { get; } | Gets keys of the dictionary. If appearance dictionary has subditionaries, then `Keys` contains (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes). |
| [SyncRoot](./syncroot/) { get; } | Gets an object that can be used to synchronize access to the dictionary. |
| [Values](./values/) { get; } | Gets the list of the dictionary values. Result collection contains the list of XForm objects. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(KeyValuePair<string, XForm>) | Adds pair with key and value into the dictionary. |
| [Add](./add/)(string, XForm) | Add X form for specifed key. |
| [Clear](./clear/)() | Removes all elements from the dictionary. |
| [Contains](./contains/)(KeyValuePair<string, XForm>) | Checks does specified key-value pair is contained in the dictionary. |
| [ContainsKey](./containskey/)(string) | Determines does this dictionary contasins specified key. |
| [CopyTo](./copyto/)(KeyValuePair<string, XForm>[], int) |  |
| [CopyTo](./copyto/)(XForm[], int) | Copies the elements of the dictionary to an Array, starting at a particular Array index. |
| [GetEnumerator](./getenumerator/)() | Returns an IDictionaryEnumerator object for the dictionary. |
| [Remove](./remove/)(KeyValuePair<string, XForm>) | Removes key/value pair from the collection. |
| [Remove](./remove/)(string) | Removes key from the dictionary. |
| [TryGetValue](./trygetvalue/)(string, out XForm) | Tries to find key in the dictionary and retreives value if found. |

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

