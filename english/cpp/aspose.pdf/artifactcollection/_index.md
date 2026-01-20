---
title: Aspose::Pdf::ArtifactCollection class
linktitle: ArtifactCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ArtifactCollection class. Class represents artifact collection in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf/artifactcollection/
---
## ArtifactCollection class


Class represents artifact collection.

```cpp
class ArtifactCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Artifact>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Artifact\>\&) override | Adds artifacts to the collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Artifact\>\>, int32_t) override | Copies colection into an array. |
| [Delete](./delete/)(System::SharedPtr\<Artifact\>) | Deletes specified artifact. |
| [Delete](./delete/)(int32_t) | Deletes artifact by its index. |
| [FindByValue](./findbyvalue/)(System::String, System::String) | Finds artifacts by custom value. |
| [get_Count](./get_count/)() const override | Gets count of artifacts in collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets if collection is readonly. Always returns false. |
| [get_IsSynchronized](./get_issynchronized/)() | Is this object synchronized. |
| [get_SyncRoot](./get_syncroot/)() const | Gets synchronization object of the collection. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator for the collection. |
| [idx_get](./idx_get/)(int32_t) | Gets artifact by index. Index is started from 1. |
| [Update](./update/)(System::SharedPtr\<Artifact\>) | Update artifact inside the collection. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
