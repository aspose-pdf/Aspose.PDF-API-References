---
title: Aspose::Pdf::EmbeddedFileCollection class
linktitle: EmbeddedFileCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::EmbeddedFileCollection class. Class representing embedded files collection in C++.'
type: docs
weight: 4500
url: /cpp/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection class


Class representing embedded files collection.

```cpp
class EmbeddedFileCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FileSpecification>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FileSpecification\>\&) override | Adds embedded file specification into collection. |
| [Add](./add/)(System::String, System::SharedPtr\<FileSpecification\>) | Adds file to embedded files with the specified key. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FileSpecification\>\>, int32_t) override | Copies array of [FileSpecification](../filespecification/) object into colleciton. |
| [Delete](./delete/)(System::String) | Delete embedded file by name. |
| [Delete](./delete/)() | Remove all embedded files from document. |
| [DeleteByKey](./deletebykey/)(System::String) | Deletes file from the collection by its key in the collection. |
| [FindByName](./findbyname/)(System::String) | Returns embedded file by its name. |
| [get_Count](./get_count/)() const override | Gets number of embedded files in collection. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [get_Keys](./get_keys/)() | Returns list of file attachment keys. |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to this collection. |
| [GetEnumerator](./getenumerator/)() override | Returns colleciton enumerator. |
| [idx_get](./idx_get/)(int32_t) | Gets embedded file by its index. |
| [idx_get](./idx_get/)(System::String) | Gets embedded file by its name. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
