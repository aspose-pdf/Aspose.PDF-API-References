---
title: Aspose::Pdf::CollectionSort::get_S method
linktitle: get_S
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionSort::get_S method. Gets the name or names of fields that the interactive PDF processor shall use to sort the items in the collection. If the value is a name, it identifies a field described in the parent collection dictionary. If the value is an array, each element of the array shall be a name that identifies a field described in the parent collection dictionary. The array form shall be used to allow additional fields to contribute to the sort, where each additional field shall be used to break ties. More specifically, if multiple collection item dictionaries have the same value for the first field named in the array, the values for successive fields named in the array shall be used for sorting, until a unique order is determined or until the named fields are exhausted in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/collectionsort/get_s/
---
## CollectionSort::get_S method


Gets the name or names of fields that the interactive PDF processor shall use to sort the items in the collection. If the value is a name, it identifies a field described in the parent collection dictionary. If the value is an array, each element of the array shall be a name that identifies a field described in the parent collection dictionary. The array form shall be used to allow additional fields to contribute to the sort, where each additional field shall be used to break ties. More specifically, if multiple collection item dictionaries have the same value for the first field named in the array, the values for successive fields named in the array shall be used for sorting, until a unique order is determined or until the named fields are exhausted.

```cpp
const System::ArrayPtr<System::String> & Aspose::Pdf::CollectionSort::get_S() const
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [CollectionSort](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
