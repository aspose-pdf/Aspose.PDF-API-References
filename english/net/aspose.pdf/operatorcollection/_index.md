---
title: "OperatorCollection Class"
linktitle: "OperatorCollection"
articleTitle: "OperatorCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.OperatorCollection class. Class represents collection of operators"
type: docs
weight: 2020
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
| [Count](./count/) { get; } | Gets count of operators in the collection. |
| [IsFastTextExtractionMode](./isfasttextextractionmode/) { get; } | Indicates wheather collection is limited to fast text extraction. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [Item](./item/) { get; set; } | Gets operator by its index. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*IOperatorSelector*) | Accepts IOperatorSelector visitor object to process operators. |
| [Add](./add/)(*Operator*) | Adds new operator into collection. |
| [Add](./add/)(*Operator[]*) | Add operators at the end of the contents operators. |
| [Add](./add/)(*ICollection<Operator>*) | Adds to collection all operators from other collection. |
| [CancelUpdate](./cancelupdate/) | Cancels last update. |
| [Clear](./clear/) | Removes all operators from list. |
| [Contains](./contains/)(*Operator*) | Returns true if the collection contains given operator. |
| [CopyTo](./copyto/)(*Operator[], int*) | Copies operators into operators list. |
| [Delete](./delete/)(*int*) | Deletes operator from collection. |
| [Delete](./delete/)(*Operator[]*) | Deletes operators from collection. |
| [Delete](./delete/)(*IList<Operator>*) | Deletes operators from collection. |
| [Dispose](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetEnumerator](./getenumerator/) | Returns enumerator for collection. |
| [Insert](./insert/)(*int, Operator*) | Inserts operator into collection. |
| [Insert](./insert/)(*int, Operator[]*) | Insert operators at the the given position. |
| [Insert](./insert/)(*int, IList<Operator>*) | Insert operators at the the given position. |
| [Remove](./remove/)(*Operator*) | Remove operator from the collection. |
| [Replace](./replace/)(*IList<Operator>*) | Replace operators in collection with other operators. |
| [ResumeUpdate](./resumeupdate/) | Resumes document update. |
| [ResumeUpdate](./resumeupdate/)(*bool*) | Resumes document update. |
| [SuppressUpdate](./suppressupdate/) | Suppresses update contents data. |
| [ToString](./tostring/) | Returns text representation of the operator. |

### See Also

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

