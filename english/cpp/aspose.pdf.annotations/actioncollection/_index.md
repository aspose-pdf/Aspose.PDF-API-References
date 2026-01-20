---
title: Aspose::Pdf::Annotations::ActionCollection class
linktitle: ActionCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ActionCollection class. Collection of actions in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/actioncollection/
---
## ActionCollection class


[Collection](../../aspose.pdf/collection/) of actions.

```cpp
class ActionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<PdfAction>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<PdfAction\>\&) override | Adds new action into colleciton. |
| [Clear](./clear/)() override | Clear collection. |
| [Contains](./contains/)(const System::SharedPtr\<PdfAction\>\&) const override | Returns true if give item presents in the collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<PdfAction\>\>, int32_t) override | Copies actions array into collection. |
| [Delete](./delete/)(int32_t) | Removes action from collection by index. |
| [Delete](./delete/)() | Delete all actions. |
| [get_Count](./get_count/)() const override | Count of actions on the collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Returns true if collection is readonly. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if object is synchronized. |
| [get_SyncRoot](./get_syncroot/)() const | Gets synchronization object. |
| [GetEnumerator](./getenumerator/)() override | Returns enumerator for collection. |
| [idx_get](./idx_get/)(int32_t) | Gets action by its index. |
| [Remove](./remove/)(const System::SharedPtr\<PdfAction\>\&) override | Removes item from collection. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
