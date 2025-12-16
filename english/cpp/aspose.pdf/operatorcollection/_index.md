---
title: Aspose::Pdf::OperatorCollection class
linktitle: OperatorCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorCollection class. Class represents collection of operators in C++.'
type: docs
weight: 12300
url: /cpp/aspose.pdf/operatorcollection/
---
## OperatorCollection class


Class represents collection of operators.

```cpp
class OperatorCollection : public Aspose::Pdf::BaseOperatorCollection,
                           public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<IOperatorSelector\>) | Accepts [IOperatorSelector](../ioperatorselector/) visitor object to process operators. |
| [Add](./add/)(const System::SharedPtr\<Operator\>\&) override | Adds new operator into collection. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) | Add operators at the end of the contents operators. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) | Adds to collection all operators from other collection. |
| [CancelUpdate](./cancelupdate/)() override | Cancels last update. This method may be called when the change should not raise contents update. |
| [Clear](./clear/)() override | Removes all operators from list. |
| [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const override | Returns true if the collection contains given operator. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) override | Copies operators into operators list. |
| [Delete](./delete/)(int32_t) | Deletes operator from collection. |
| [Delete](./delete/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>) | Deletes operators from collection. |
| [Delete](./delete/)(System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>) | Deletes operators from collection. |
| [Dispose](./dispose/)() override | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [get_Count](./get_count/)() const override | Gets count of operators in the collection. |
| [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const override | Indicates wheather collection is limited to fast text extraction. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the collection is read-only. |
| [GetEnumerator](./getenumerator/)() override | Returns enumerator for collection. |
| [idx_get](./idx_get/)(int32_t) override | Gets operator by its index. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) override | Gets operator by its index. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) override | Inserts operator into collection. |
| [Insert](./insert/)(int32_t, System::ArrayPtr\<System::SharedPtr\<Operator\>\>) | Insert operators at the the given position. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>) | Insert operators at the the given position. |
| [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) override | Remove operator from the collection. |
| [Replace](./replace/)(System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>) | Replace operators in collection with other operators. |
| [ResumeUpdate](./resumeupdate/)(bool) | Resumes document update. Updates contents stream in case there are any pending changes. Marks all operators as "changed" if invalidate parameter is true. |
| [ResumeUpdate](./resumeupdate/)() override | Resumes document update. Updates contents stream in case there are any pending changes. |
| [SuppressUpdate](./suppressupdate/)() override | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |
| [ToString](./tostring/)() const override | Returns text representation of the operator. |
## See Also

* Class [BaseOperatorCollection](../baseoperatorcollection/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
