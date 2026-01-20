---
title: Aspose::Pdf::Text::FontCollection class
linktitle: FontCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontCollection class. Represents font collection in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.text/fontcollection/
---
## FontCollection class


Represents font collection.

```cpp
class FontCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Font>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Font\>, System::String\&) | Adds new font to font resources and returns automatically assigned name of font resource. |
| [Contains](./contains/)(const System::String\&) const | Checks if font exists in font collection. |
| [Contains](./contains/)(const System::SharedPtr\<Font\>\&) const override | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Font\>\>, int32_t) override | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [get_Count](./get_count/)() const override | Gets the number of [Font](../font/) object elements actually contained in the collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator for the entire collection. |
| [idx_get](./idx_get/)(int32_t) | Gets the font element at the specified index. |
| [idx_get](./idx_get/)(System::String) | Gets font from the collection by font name. Exception is thrown if font was not found. |
| [Remove](./remove/)(const System::SharedPtr\<Font\>\&) override | Deletes specified item from collection. |
## Remarks


[Font](../font/) collections represented by [FontCollection](./) class are used in several scenarios. For example, in resources with [Resources::Fonts](../) property. 
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
