---
title: Aspose::Pdf::Collection class
linktitle: Collection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Collection class. Represents class for Collection(12.3.5 Collections) in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf/collection/
---
## Collection class


Represents class for [Collection](./)(12.3.5 [Collections](../../aspose.pdf.collections/)).

```cpp
class Collection : public Aspose::Pdf::EmbeddedFileCollection
```

## Methods

| Method | Description |
| --- | --- |
| [Add](../embeddedfilecollection/add/)(const System::SharedPtr\<FileSpecification\>\&) override | Adds embedded file specification into collection. |
| [Add](../embeddedfilecollection/add/)(System::String, System::SharedPtr\<FileSpecification\>) | Adds file to embedded files with the specified key. |
| [Collection](./collection/)() | Initializes new [Collection](./) object. |
| [CopyTo](../embeddedfilecollection/copyto/)(System::ArrayPtr\<System::SharedPtr\<FileSpecification\>\>, int32_t) override | Copies array of [FileSpecification](../filespecification/) object into colleciton. |
| [Delete](../embeddedfilecollection/delete/)(System::String) | Delete embedded file by name. |
| [Delete](../embeddedfilecollection/delete/)() | Remove all embedded files from document. |
| [DeleteByKey](../embeddedfilecollection/deletebykey/)(System::String) | Deletes file from the collection by its key in the collection. |
| [FindByName](../embeddedfilecollection/findbyname/)(System::String) | Returns embedded file by its name. |
| [get_Count](../embeddedfilecollection/get_count/)() const override | Gets number of embedded files in collection. |
| [get_DefaultEntry](./get_defaultentry/)() | Default embedded file name. |
| [get_IsSynchronized](../embeddedfilecollection/get_issynchronized/)() | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [get_Keys](../embeddedfilecollection/get_keys/)() | Returns list of file attachment keys. |
| [get_Schema](./get_schema/)() | Gets a "Schema" of a document collection. |
| [get_SyncRoot](../embeddedfilecollection/get_syncroot/)() const | Gets an object that can be used to synchronize access to this collection. |
| [GetEnumerator](../embeddedfilecollection/getenumerator/)() override | Returns colleciton enumerator. |
| [GetSortedCollection](./getsortedcollection/)() | Gets a collection of files sorted according to the specification. |
| [idx_get](../embeddedfilecollection/idx_get/)(int32_t) | Gets embedded file by its index. |
| [idx_get](../embeddedfilecollection/idx_get/)(System::String) | Gets embedded file by its name. |
## See Also

* Class [EmbeddedFileCollection](../embeddedfilecollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
