---
title: "OperatorCollection Class"
linktitle: "OperatorCollection"
articleTitle: "OperatorCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.OperatorCollection class. Class represents collection of operators"
type: docs
weight: 1980
url: "/net/aspose.pdf/operatorcollection/"
keywords: "OperatorCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OperatorCollection class

Class represents collection of operators

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| override [Count](./count/) { get; } | Gets count of operators in the collection. |
| override [IsFastTextExtractionMode](./isfasttextextractionmode/) { get; } | Indicates wheather collection is limited to fast text extraction |
| override [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| override [Item](./item/) { get; set; } | Gets operator by its index. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(IOperatorSelector) | Accepts IOperatorSelector visitor object to process operators. |
| [Add](./add/)(ICollection<Operator>) | Adds to collection all operators from other collection. |
| override [Add](./add/)(Operator) | Adds new operator into collection. |
| [Add](./add/)(Operator[]) | Add operators at the end of the contents operators. |
| override [CancelUpdate](./cancelupdate/)() | Cancels last update. This method may be called when the change should not raise contents update. |
| override [Clear](./clear/)() | Removes all operators from list. |
| override [Contains](./contains/)(Operator) | Returns true if the collection contains given operator. |
| override [CopyTo](./copyto/)(Operator[], int) | Copies operators into operators list. |
| [Delete](./delete/)(IList<Operator>) | Deletes operators from collection. |
| [Delete](./delete/)(int) | Deletes operator from collection. |
| [Delete](./delete/)(Operator[]) | Deletes operators from collection. |
| [Dispose](./dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| override [GetEnumerator](./getenumerator/)() | Returns enumerator for collection |
| [Insert](./insert/)(int, IList<Operator>) | Insert operators at the the given position. |
| override [Insert](./insert/)(int, Operator) | Inserts operator into collection. |
| [Insert](./insert/)(int, Operator[]) | Insert operators at the the given position. |
| override [Remove](./remove/)(Operator) | Remove operator from the collection. |
| [Replace](./replace/)(IList<Operator>) | Replace operators in collection with other operators. |
| override [ResumeUpdate](./resumeupdate/)() | Resumes document update. Updates contents stream in case there are any pending changes. |
| [ResumeUpdate](./resumeupdate/)(bool) | Resumes document update. Updates contents stream in case there are any pending changes. Marks all operators as "changed" if invalidate parameter is true. |
| override [SuppressUpdate](./suppressupdate/)() | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |
| override [ToString](./tostring/)() | Returns text representation of the operator. |

### See Also

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

