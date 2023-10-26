---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OperatorCollection class. Class represents collection of operators
type: docs
weight: 4920
url: /net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

Class represents collection of operators

```csharp
public class OperatorCollection : BaseOperatorCollection
```

## Properties

| Name | Description |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Gets count of operators in the collection. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indicates wheather collection is limited to fast text extraction |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Gets operator by its index. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Accepts IOperatorSelector visitor object to process operators. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Adds to collection all operators from other collection. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Adds new operator into collection. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Add operators at the end of the contents operators. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Cancels last update. This method may be called when the change should not raise contents update. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Removes all operators from list. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Returns true if the collection contains given operator. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Copies operators into operators list. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Deletes operators from collection. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Deletes operator from collection. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Deletes operators from collection. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Returns enumerator for collection |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Insert operators at the the given position. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Inserts operator into collection. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Insert operators at the the given position. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Remove operator from the collection. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Replace operators in collection with other operators. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Resumes document update. Updates contents stream in case there are any pending changes. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Resumes document update. Updates contents stream in case there are any pending changes. Marks all operators as "changed" if invalidate parameter is true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Returns text representation of the operator. |

### See Also

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


