---
title: Aspose::Pdf::CollectionSort class
linktitle: CollectionSort
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionSort class. Represents a class for a collection sort definition in C++.'
type: docs
weight: 2900
url: /cpp/aspose.pdf/collectionsort/
---
## CollectionSort class


Represents a class for a collection sort definition.

```cpp
class CollectionSort : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CollectionSort](./collectionsort/)() | Creates an instance of collection sort class. |
| [CollectionSort](./collectionsort/)(System::SharedPtr\<Engine::Data::IPdfDictionary\>) | Creates an instance of collection sort class. |
| [get_A](./get_a/)() const | Gets the sort ordering value. If the value is a boolean, it specifies whether the interactive PDF processor shall sort the items in the collection in ascending order (true) or descending order (false). If the value is an array, each element of the array shall be a boolean value that specifies whether the entry at the same index in the S array shall be sorted in ascending or descending order. If the number of entries in the A array is larger than the number of entries in the S array the extra entries in the A array shall be ignored. If the number of entries in the A array is less than the number of entries in the S array the missing entries in the A array shall be assumed to be true. Default value: **true** |
| [get_S](./get_s/)() const | Gets the name or names of fields that the interactive PDF processor shall use to sort the items in the collection. If the value is a name, it identifies a field described in the parent collection dictionary. If the value is an array, each element of the array shall be a name that identifies a field described in the parent collection dictionary. The array form shall be used to allow additional fields to contribute to the sort, where each additional field shall be used to break ties. More specifically, if multiple collection item dictionaries have the same value for the first field named in the array, the values for successive fields named in the array shall be used for sorting, until a unique order is determined or until the named fields are exhausted. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
