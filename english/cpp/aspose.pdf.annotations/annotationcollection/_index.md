---
title: Aspose::Pdf::Annotations::AnnotationCollection class
linktitle: AnnotationCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AnnotationCollection class. Class representing annotation collection in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.annotations/annotationcollection/
---
## AnnotationCollection class


Class representing annotation collection.

```cpp
class AnnotationCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Annotation>>
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) | Accepts visitor to process annotation. |
| [Add](./add/)(System::SharedPtr\<Annotation\>, bool) | Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&) override | Adds annotation to the collection. |
| [Clear](./clear/)() override | Deletes all annotations from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<Annotation\>\&) const override | Checks if specified annotation belong to collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Annotation\>\>, int32_t) override | Copies array of annotations into collection. |
| [Delete](./delete/)(int32_t) | Deletes annotation from the collection by index. |
| [Delete](./delete/)() | Deletes all annotations from the collection. |
| [Delete](./delete/)(System::SharedPtr\<Annotation\>) | Deletes specified annotation from the collection. |
| [FindByName](./findbyname/)(System::String) | Returns annotation by its name. |
| [get_Count](./get_count/)() const override | Gets count of annotations in collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating if collection is readonly. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to the [Aspose.Pdf.Annotations.AnnotationCollection](./) is synchronized (thread safe). |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to [Aspose.Pdf.Annotations.AnnotationCollection](./). |
| [GetEnumerator](./getenumerator/)() override | Returns collection enumerator. |
| [idx_get](./idx_get/)(int32_t) | The index of the element to get. |
| [Remove](./remove/)(const System::SharedPtr\<Annotation\>\&) override | Deletes specified annotation from the collection. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
