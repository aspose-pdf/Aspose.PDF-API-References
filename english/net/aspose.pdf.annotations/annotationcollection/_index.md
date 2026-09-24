---
title: "AnnotationCollection Class"
linktitle: "AnnotationCollection"
articleTitle: "AnnotationCollection"
second_title: "Aspose.PDF for .NET"
description: "Class representing annotation collection."
type: docs
weight: 50
url: "/net/aspose.pdf.annotations/annotationcollection/"
keywords: "AnnotationCollection, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AnnotationCollection class

Class representing annotation collection.

```csharp
public sealed class AnnotationCollection : IEnumerable
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets count of annotations in collection. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating if collection is readonly. |
| [IsSynchronized](./issynchronized/) { get; } | Gets a value indicating whether access to the Aspose.Pdf.Annotations.AnnotationCollection is synchronized (thread safe). |
| [Item](./item/) { get; } |  |
| [SyncRoot](./syncroot/) { get; } | Gets an object that can be used to synchronize access to Aspose.Pdf.Annotations.AnnotationCollection. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts visitor to process annotation. |
| [Add](./add/)(*Annotation*) | Adds annotation to the collection. |
| [Add](./add/)(*Annotation, bool*) | Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly. |
| [Clear](./clear/) | Deletes all annotations from the collection. |
| [Contains](./contains/)(*Annotation*) | Checks if specified annotation belong to collection. |
| [CopyTo](./copyto/)(*Annotation[], int*) | Copies array of annotations into collection. |
| [Delete](./delete/) | Deletes all annotations from the collection. |
| [Delete](./delete/)(*int*) | Deletes annotation from the collection by index. |
| [Delete](./delete/)(*Annotation*) | Deletes specified annotation from the collection. |
| [FindByName](./findbyname/)(*string*) | Returns annotation by its name. |
| [GetEnumerator](./getenumerator/) | Returns collection enumerator. |
| [Remove](./remove/)(*Annotation*) | Deletes specified annotation from the collection. |

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

