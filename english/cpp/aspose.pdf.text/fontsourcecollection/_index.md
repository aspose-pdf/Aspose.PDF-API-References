---
title: Aspose::Pdf::Text::FontSourceCollection class
linktitle: FontSourceCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontSourceCollection class. Represents font sources collection in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.text/fontsourcecollection/
---
## FontSourceCollection class


Represents font sources collection.

```cpp
class FontSourceCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSource>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSource\>\&) override | Adds new font source object to the collection. |
| [Clear](./clear/)() override | Clears the font source collection. |
| [Contains](./contains/)(const System::SharedPtr\<FontSource\>\&) const override | Determines whether an element is in the collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSource\>\>, int32_t) override | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [Delete](./delete/)(System::SharedPtr\<FontSource\>) | Deletes the font source element. |
| [get_Count](./get_count/)() const override | Gets the number of [Font](../font/) object elements actually contained in the collection. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator for the entire collection. |
| [idx_get](./idx_get/)(int32_t) | Gets the font element at the specified index. |
| [Remove](./remove/)(const System::SharedPtr\<FontSource\>\&) override | Deletes the font source element. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
