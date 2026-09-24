---
title: "Collection Class"
linktitle: "Collection"
articleTitle: "Collection"
second_title: "Aspose.PDF for .NET"
description: "Represents class for Collection(12.3.5 Collections)."
type: docs
weight: 310
url: "/net/aspose.pdf/collection/"
keywords: "Collection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Collection class

Represents class for Collection(12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## Constructors

| Name | Description |
| --- | --- |
| [Collection](./collection/#constructor) | Initializes new Collection object. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Gets number of embedded files in collection. *(Inherited from EmbeddedFileCollection)* |
| [DefaultEntry](./defaultentry/) { get; } | Default embedded file name. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Gets a value indicating whether access to this collection is synchronized (thread safe). *(Inherited from EmbeddedFileCollection)* |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | *(Inherited from EmbeddedFileCollection)* |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Returns list of file attachment keys. *(Inherited from EmbeddedFileCollection)* |
| [Schema](./schema/) { get; } | Gets a "Schema" of a document collection. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Gets an object that can be used to synchronize access to this collection. *(Inherited from EmbeddedFileCollection)* |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(*FileSpecification*) | Adds embedded file specification into collection. *(Inherited from EmbeddedFileCollection)* |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(*string, FileSpecification*) | Adds file to embedded files with the specified key. *(Inherited from EmbeddedFileCollection)* |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(*FileSpecification[], int*) | Copies array of FileSpecification object into colleciton. *(Inherited from EmbeddedFileCollection)* |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/) | Remove all embedded files from document. *(Inherited from EmbeddedFileCollection)* |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(*string*) | Delete embedded file by name. *(Inherited from EmbeddedFileCollection)* |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(*string*) | Deletes file from the collection by its key in the collection. *(Inherited from EmbeddedFileCollection)* |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(*string*) | Returns embedded file by its name. *(Inherited from EmbeddedFileCollection)* |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/) | Returns colleciton enumerator. *(Inherited from EmbeddedFileCollection)* |
| [GetSortedCollection](./getsortedcollection/) | Gets a collection of files sorted according to the specification. |

### See Also

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

