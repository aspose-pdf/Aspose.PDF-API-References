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
product_version: "26.9"
---
## Metadata class

Provides access to XMP metadata stream.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Gets count of elements in the collection. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Gets the dictionary of extension fields. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Checks if colleciton has fixed size. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Checks if collection is read-only. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Checks if collection is synchronized. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Gets or sets data from metadata. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Gets collection of metadata keys. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Gets namespace manager. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Gets collection synchronization object. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Gets values in the metadata. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(string, XmpValue) | Adds value to metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, object) | Adds value to metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpPdfAExtensionObject) | Adds pdf extension to metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(KeyValuePair&lt;string, XmpValue&gt;) | Adds pair with key and value into the dictionary. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Clears metadata. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(string) | Checks does key is contained in metadata. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Checks does specified key-value pair is contained in the dictionary. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Determines does this dictionary contasins specified key. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Returns dictionary enumerator. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Returns namespace URI by prefix. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Returns prefix by namespace URI. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registers namespace URI. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registers namespace URI. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(string) | Removes entry from metadata. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(KeyValuePair&lt;string, XmpValue&gt;) | Removes key/value pair from the colleciton. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Tries to find key in the dictionary and retreives value if found. |

### See Also

* class [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

