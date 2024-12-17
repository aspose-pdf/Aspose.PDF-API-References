---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection class. Represents base class for operator collection
type: docs
weight: 2830
url: /net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

Represents base class for operator collection.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Properties

| Name | Description |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Gets count of operators in the collection. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indicates wheather collection is limited to fast text extraction |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Returns true if collection is read only. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Gets operator by its index. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Adds new operator into collection. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Cancels last update. This method may be called when the change should not raise contents update. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Clears collection. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Checks if operator exists in collection. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copies operators into operators list. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Returns enumerator for collection |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Inserts operator into collection. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Removes operator from collection. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Resumes document update. Updates contents stream in case there are any pending changes. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |

### See Also

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


