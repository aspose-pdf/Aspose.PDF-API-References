---
title: "Metadata Class"
linktitle: "Metadata"
articleTitle: "Metadata"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Metadata class. Provides access to XMP metadata stream."
type: docs
weight: 1860
url: "/net/aspose.pdf/metadata/"
keywords: "Metadata, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Metadata class

Provides access to XMP metadata stream.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets count of elements in the collection. |
| [ExtensionFields](./extensionfields/) { get; } | Gets the dictionary of extension fields. |
| [IsFixedSize](./isfixedsize/) { get; } | Checks if colleciton has fixed size. |
| [IsReadOnly](./isreadonly/) { get; } | Checks if collection is read-only. |
| [IsSynchronized](./issynchronized/) { get; } | Checks if collection is synchronized. |
| [Item](./item/) { get; set; } | Gets or sets data from metadata. |
| [Keys](./keys/) { get; } | Gets collection of metadata keys. |
| [NamespaceManager](./namespacemanager/) { get; } | Gets namespace manager. |
| [SyncRoot](./syncroot/) { get; } | Gets collection synchronization object. |
| [Values](./values/) { get; } | Gets values in the metadata. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(KeyValuePair<string, XmpValue>) | Adds pair with key and value into the dictionary. |
| [Add](./add/)(string, object) | Adds value to metadata. |
| [Add](./add/)(string, XmpPdfAExtensionObject) | Adds pdf extension to metadata. |
| [Add](./add/)(string, XmpValue) | Adds value to metadata. |
| [Clear](./clear/)() | Clears metadata. |
| [Contains](./contains/)(KeyValuePair<string, XmpValue>) | Checks does specified key-value pair is contained in the dictionary. |
| [Contains](./contains/)(string) | Checks does key is contained in metadata. |
| [ContainsKey](./containskey/)(string) | Determines does this dictionary contasins specified key. |
| [CopyTo](./copyto/)(KeyValuePair<string, XmpValue>[], int) |  |
| [GetEnumerator](./getenumerator/)() | Returns dictionary enumerator. |
| [GetNamespaceUriByPrefix](./getnamespaceuribyprefix/)(string) | Returns namespace URI by prefix. |
| [GetPrefixByNamespaceUri](./getprefixbynamespaceuri/)(string) | Returns prefix by namespace URI. |
| [RegisterNamespaceUri](./registernamespaceuri/)(string, string) | Registers namespace URI. |
| [RegisterNamespaceUri](./registernamespaceuri/)(string, string, string) | Registers namespace URI. |
| [Remove](./remove/)(KeyValuePair<string, XmpValue>) | Removes key/value pair from the colleciton. |
| [Remove](./remove/)(string) | Removes entry from metadata. |
| [TryGetValue](./trygetvalue/)(string, out XmpValue) | Tries to find key in the dictionary and retreives value if found. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

