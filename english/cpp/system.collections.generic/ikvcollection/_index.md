---
title: System::Collections::Generic::IKVCollection class
linktitle: IKVCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IKVCollection class. Interface of container containing keys or values of the dictionary-like container. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.collections.generic/ikvcollection/
---
## IKVCollection class


Interface of container containing keys or values of the dictionary-like container. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IKVCollection : public System::Collections::Generic::IList<T>
```


| Parameter | Description |
| --- | --- |
| T | [KeyValuePair](../keyvaluepair/) type. |
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const T\&) override | Adds item to container. |
| [Clear](./clear/)() override | Deletes all elements from container. |
| [Contains](./contains/)(const T\&) const override | Checks if item is present in container. |
| virtual [get_Count](./get_count/)() const | Gets number of elements in container. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Checks if container is read only. |
| virtual [GetEnumerator](./getenumerator/)() | RTTI information. |
| virtual [idx_get](./idx_get/)(int) const | Getter function. |
| [idx_set](./idx_set/)(int, T) override | Setter function. |
| [IndexOf](./indexof/)(const T\&) const override | Gets index of item in container. |
| [Insert](./insert/)(int, const T\&) override | Inserts item at specified position. |
| [Remove](./remove/)(const T\&) override | Removes item from container. |
| [RemoveAt](./removeat/)(int) override | Removes item at specified position. |

## See Also

* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
