---
title: Aspose::Pdf::Text::CharInfoCollection class
linktitle: CharInfoCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::CharInfoCollection class. Represents CharInfo objects collection in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class


Represents [CharInfo](../charinfo/) objects collection.

```cpp
class CharInfoCollection : public System::Collections::Generic::ICollection<System::SharedPtr<CharInfo>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<CharInfo\>\&) override | [Collection](../../aspose.pdf/collection/) is read-only, throws NotImplementedException
. |
| [Clear](./clear/)() override | [Collection](../../aspose.pdf/collection/) is read-only. Always throws NotImplementedException. |
| [Contains](./contains/)(const System::SharedPtr\<CharInfo\>\&) const override | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<CharInfo\>\>, int32_t) override | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [get_Count](./get_count/)() const override | Gets the number of [CharInfo](../charinfo/) object elements actually contained in the collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator for the entire collection. |
| [idx_get](./idx_get/)(int32_t) | Gets the [CharInfo](../charinfo/) element at the specified index. |
| [Remove](./remove/)(const System::SharedPtr\<CharInfo\>\&) override | [Collection](../../aspose.pdf/collection/) is read-only, throws NotImplementedException
. |
## Remarks


Provides access to positioning information of text segment characters. 
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
