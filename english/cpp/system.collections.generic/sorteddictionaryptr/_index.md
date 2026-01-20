---
title: System::Collections::Generic::SortedDictionaryPtr class
linktitle: SortedDictionaryPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::SortedDictionaryPtr class. Sorted dictionary pointer with access operators. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 4100
url: /cpp/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr class


Sorted dictionary pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<T0>
```

## Methods

| Method | Description |
| --- | --- |
| [operator[]](./operator[]/)(const T\&) const | Accessor function. |
| [SortedDictionaryPtr](./sorteddictionaryptr/)() | Constructs null pointer. |
| [SortedDictionaryPtr](./sorteddictionaryptr/)(const SharedPtr\<SortedDictionary\<T, V\>\>\&) | Constructs pointer to specified sorted dictionary. |
## See Also

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
