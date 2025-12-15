---
title: Aspose::Pdf::XFormCollection class
linktitle: XFormCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XFormCollection class. Class represents collection of XFormCollection in C++.'
type: docs
weight: 19500
url: /cpp/aspose.pdf/xformcollection/
---
## XFormCollection class


Class represents collection of [XFormCollection](./).

```cpp
class XFormCollection : public System::Collections::Generic::ICollection<System::SharedPtr<XForm>>,
                        public Aspose::Pdf::ISupportsMemoryCleanup
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XForm\>\&) override | Adds new [XForm](../xform/) into collection. |
| [Clear](./clear/)() override | Clears all items from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<XForm\>\&) const override | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<XForm\>\>, int32_t) override | Copies [XFormCollection](./) into collection. |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(System::SharedPtr\<XForm\>) |  |
| [Delete](./delete/)(int32_t) | Delete [XForm](../xform/) from collection. |
| [Delete](./delete/)() | Deletes all XForms from the collection. |
| [Delete](./delete/)(System::String) | Deletes [XForm](../xform/) from collection by form name. |
| [FreeMemory](./freememory/)() override | Clears cached data, frees memory etc. |
| [get_Count](./get_count/)() const override | Gets count of XForms in collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if object is synchronized. |
| [get_SyncRoot](./get_syncroot/)() const | Synchronization object. |
| [GetEnumerator](./getenumerator/)() override | Returns collection enumerator. |
| [GetFormName](./getformname/)(System::SharedPtr\<XForm\>) | Returns name of the form in this form collection. |
| [idx_get](./idx_get/)(int32_t) | Returns [XForm](../xform/) by index. |
| [idx_get](./idx_get/)(System::String) | Returns [XForm](../xform/) by its name. Exception is thrown if [XForm](../xform/) with specified name is not found. |
| [Remove](./remove/)(const System::SharedPtr\<XForm\>\&) override | Deletes specified item from collection. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
