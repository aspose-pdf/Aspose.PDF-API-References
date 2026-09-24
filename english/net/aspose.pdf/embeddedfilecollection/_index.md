---
title: "EmbeddedFileCollection Class"
linktitle: "EmbeddedFileCollection"
articleTitle: "EmbeddedFileCollection"
second_title: "Aspose.PDF for .NET"
description: "Class representing embedded files collection."
type: docs
weight: 720
url: "/net/aspose.pdf/embeddedfilecollection/"
keywords: "EmbeddedFileCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## EmbeddedFileCollection class

Class representing embedded files collection.

```csharp
public class EmbeddedFileCollection : IEnumerable
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets number of embedded files in collection. |
| [IsSynchronized](./issynchronized/) { get; } | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [Item](./item/) { get; } |  |
| [Item](./item/) { get; } |  |
| [Keys](./keys/) { get; } | Returns list of file attachment keys. |
| [SyncRoot](./syncroot/) { get; } | Gets an object that can be used to synchronize access to this collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*FileSpecification*) | Adds embedded file specification into collection. |
| [Add](./add/)(*string, FileSpecification*) | Adds file to embedded files with the specified key. |
| [CopyTo](./copyto/)(*FileSpecification[], int*) | Copies array of FileSpecification object into colleciton. |
| [Delete](./delete/) | Remove all embedded files from document. |
| [Delete](./delete/)(*string*) | Delete embedded file by name. |
| [DeleteByKey](./deletebykey/)(*string*) | Deletes file from the collection by its key in the collection. |
| [FindByName](./findbyname/)(*string*) | Returns embedded file by its name. |
| [GetEnumerator](./getenumerator/) | Returns colleciton enumerator. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

