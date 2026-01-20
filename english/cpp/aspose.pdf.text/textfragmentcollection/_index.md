---
title: Aspose::Pdf::Text::TextFragmentCollection class
linktitle: TextFragmentCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragmentCollection class. Represents a text fragments collection in C++.'
type: docs
weight: 4500
url: /cpp/aspose.pdf.text/textfragmentcollection/
---
## TextFragmentCollection class


Represents a text fragments collection.

```cpp
class TextFragmentCollection : public System::Collections::Generic::ICollection<System::SharedPtr<TextFragment>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<TextFragment\>\&) override | Adds the text fragment element at the specified index. |
| [Clear](./clear/)() override | Clears all items from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<TextFragment\>\&) const override | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<TextFragment\>\>, int32_t) override | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [get_Count](./get_count/)() const override | Gets the number of [TextFragment](../textfragment/) object elements actually contained in the collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator for the entire collection. |
| [idx_get](./idx_get/)(int32_t) | Gets the text fragment element at the specified index. |
| [Remove](./remove/)(const System::SharedPtr\<TextFragment\>\&) override | Deletes specified item from collection. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
