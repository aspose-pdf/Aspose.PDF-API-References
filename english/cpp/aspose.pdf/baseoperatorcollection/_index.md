---
title: Aspose::Pdf::BaseOperatorCollection class
linktitle: BaseOperatorCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::BaseOperatorCollection class. Represents base class for operator collection in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class


Represents base class for operator collection.

```cpp
class BaseOperatorCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Operator>>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<Operator\>\&) | Adds new operator into collection. |
| virtual [CancelUpdate](./cancelupdate/)() | Cancels last update. This method may be called when the change should not raise contents update. |
| virtual [Clear](./clear/)() | Clears collection. |
| virtual [Contains](./contains/)(const System::SharedPtr\<Operator\>\&) const | Checks if operator exists in collection. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Operator\>\>, int32_t) | Copies operators into operators list. |
| virtual [get_Count](./get_count/)() const | Gets count of operators in the collection. |
| virtual [get_IsFastTextExtractionMode](./get_isfasttextextractionmode/)() const | Indicates wheather collection is limited to fast text extraction. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Returns true if collection is read only. |
| virtual [GetEnumerator](./getenumerator/)() | Returns enumerator for collection. |
| virtual [idx_get](./idx_get/)(int32_t) | Gets operator by its index. |
| virtual [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Operator\>) | Gets operator by its index. |
| virtual [Insert](./insert/)(int32_t, System::SharedPtr\<Operator\>) | Inserts operator into collection. |
| virtual [Remove](./remove/)(const System::SharedPtr\<Operator\>\&) | Removes operator from collection. |
| virtual [ResumeUpdate](./resumeupdate/)() | Resumes document update. Updates contents stream in case there are any pending changes. |
| virtual [SuppressUpdate](./suppressupdate/)() | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
