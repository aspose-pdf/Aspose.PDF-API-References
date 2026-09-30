---
title: "BaseOperatorCollection Class"
linktitle: "BaseOperatorCollection"
articleTitle: "BaseOperatorCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.BaseOperatorCollection class. Represents base class for operator collection."
type: docs
weight: 120
url: "/net/aspose.pdf/baseoperatorcollection/"
keywords: "BaseOperatorCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BaseOperatorCollection class

Represents base class for operator collection.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Properties

| Name | Description |
| --- | --- |
| abstract [Count](./count/) { get; } | Gets count of operators in the collection. |
| abstract [IsFastTextExtractionMode](./isfasttextextractionmode/) { get; } | Indicates wheather collection is limited to fast text extraction |
| abstract [IsReadOnly](./isreadonly/) { get; } | Returns true if collection is read only. |
| abstract [Item](./item/) { get; set; } | Gets operator by its index. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Add](./add/)(Operator) | Adds new operator into collection. |
| abstract [CancelUpdate](./cancelupdate/)() | Cancels last update. This method may be called when the change should not raise contents update. |
| abstract [Clear](./clear/)() | Clears collection. |
| abstract [Contains](./contains/)(Operator) | Checks if operator exists in collection. |
| abstract [CopyTo](./copyto/)(Operator[], int) | Copies operators into operators list. |
| abstract [GetEnumerator](./getenumerator/)() | Returns enumerator for collection |
| abstract [Insert](./insert/)(int, Operator) | Inserts operator into collection. |
| abstract [Remove](./remove/)(Operator) | Removes operator from collection. |
| abstract [ResumeUpdate](./resumeupdate/)() | Resumes document update. Updates contents stream in case there are any pending changes. |
| abstract [SuppressUpdate](./suppressupdate/)() | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

