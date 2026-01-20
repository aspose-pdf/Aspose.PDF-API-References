---
title: System::Collections::ObjectModel::KeyedCollection class
linktitle: KeyedCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::ObjectModel::KeyedCollection class. Abstract collection of elements with embedded keys. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.collections.objectmodel/keyedcollection/
---
## KeyedCollection class


Abstract collection of elements with embedded keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename TKey,typename TItem>class KeyedCollection : public System::Collections::ObjectModel::Collection<TItem>
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TItem | value type. |
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const TItem\&) override | Add item to container end. |
| [Contains](./contains/)(TKey) | Checks if key is present in container. |
| [get_Comparer](./get_comparer/)() | Gets comparer. |
| [idx_get](./idx_get/)(TKey) | Gets item at specific index. |
| [Remove](./remove/)(TKey) | Removes key from container. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Makes specific template argument to be treated as weak pointer instead of shared pointer (if applicable). |
## Fields

| Field | Description |
| --- | --- |
| static [defaultThreshold](./defaultthreshold/) | Lookup dictionary creation threshold, default. |

## See Also

* Class [Collection](../collection/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
