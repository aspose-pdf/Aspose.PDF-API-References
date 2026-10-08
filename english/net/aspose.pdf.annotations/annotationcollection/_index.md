---
title: "AnnotationCollection Class"
linktitle: "AnnotationCollection"
articleTitle: "AnnotationCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.AnnotationCollection class. Class representing annotation collection."
type: docs
weight: 50
url: "/net/aspose.pdf.annotations/annotationcollection/"
keywords: "AnnotationCollection, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## AnnotationCollection class

Class representing annotation collection.

```csharp
public sealed class AnnotationCollection : ICollection<Annotation>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.annotations/annotationcollection/count/) { get; } | Gets count of annotations in collection. |
| [IsReadOnly](../../aspose.pdf.annotations/annotationcollection/isreadonly/) { get; } | Gets a value indicating if collection is readonly. |
| [IsSynchronized](../../aspose.pdf.annotations/annotationcollection/issynchronized/) { get; } | Gets a value indicating whether access to the Aspose.Pdf.Annotations.AnnotationCollection is synchronized (thread safe). |
| [Item](../../aspose.pdf.annotations/annotationcollection/item/) { get; } | The index of the element to get. |
| [SyncRoot](../../aspose.pdf.annotations/annotationcollection/syncroot/) { get; } | Gets an object that can be used to synchronize access to Aspose.Pdf.Annotations.AnnotationCollection. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/annotationcollection/accept/)(AnnotationSelector) | Accepts visitor to process annotation. |
| [Add](../../aspose.pdf.annotations/annotationcollection/add/#add)(Annotation, bool) | Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly. |
| [Add](../../aspose.pdf.annotations/annotationcollection/add/#add_1)(Annotation) | Adds annotation to the collection. |
| [Clear](../../aspose.pdf.annotations/annotationcollection/clear/)() | Deletes all annotations from the collection. |
| [Contains](../../aspose.pdf.annotations/annotationcollection/contains/)(Annotation) | Checks if specified annotation belong to collection. |
| [CopyTo](../../aspose.pdf.annotations/annotationcollection/copyto/)(Annotation[], int) | Copies array of annotations into collection. |
| [Delete](../../aspose.pdf.annotations/annotationcollection/delete/#delete)(int) | Deletes annotation from the collection by index. |
| [Delete](../../aspose.pdf.annotations/annotationcollection/delete/#delete_1)() | Deletes all annotations from the collection. |
| [Delete](../../aspose.pdf.annotations/annotationcollection/delete/#delete_2)(Annotation) | Deletes specified annotation from the collection. |
| [FindByName](../../aspose.pdf.annotations/annotationcollection/findbyname/)(string) | Returns annotation by its name. |
| [GetEnumerator](../../aspose.pdf.annotations/annotationcollection/getenumerator/)() | Returns collection enumerator. |
| [Remove](../../aspose.pdf.annotations/annotationcollection/remove/)(Annotation) | Deletes specified annotation from the collection. |

### See Also

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

