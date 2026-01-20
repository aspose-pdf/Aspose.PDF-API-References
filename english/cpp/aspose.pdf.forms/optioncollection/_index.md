---
title: Aspose::Pdf::Forms::OptionCollection class
linktitle: OptionCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::OptionCollection class. Class representing collection of options of the choice field in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.forms/optioncollection/
---
## OptionCollection class


Class representing collection of options of the choice field.

```cpp
class OptionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Option>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Option\>\&) override | Adds item in collection, throws NotImplementedException
. |
| [Clear](./clear/)() override | Removes all items from collection. |
| [Contains](./contains/)(const System::SharedPtr\<Option\>\&) const override | Checks if item exists in collection, throws NotImplementedException
. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Option\>\>, int32_t) override | Copies options into array. |
| [get](./get/)(int32_t) | Gets option by index. |
| [get](./get/)(System::String) | Gets option from colleciton by option name. |
| [get_Count](./get_count/)() const override | Gets number of options. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating if collection is readonly. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true of object is synchronized. |
| [get_SyncRoot](./get_syncroot/)() const | Synchronization object of the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns enumerator for options in collection. |
| [idx_get](./idx_get/)(int32_t) | Gets option by index. |
| [idx_get](./idx_get/)(System::String) | Gets option by its name. |
| [Remove](./remove/)(const System::SharedPtr\<Option\>\&) override | Removes item from collection, throws NotImplementedException
. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
