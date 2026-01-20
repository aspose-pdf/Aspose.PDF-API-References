---
title: System::Collections::Generic::_KeyCollection class
linktitle: _KeyCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::_KeyCollection class. Collection of Dictionary''s keys. References collection, doesn''t copy anything. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.collections.generic/_keycollection/
---
## _KeyCollection class


Collection of [Dictionary](../dictionary/)'s keys. References collection, doesn't copy anything. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Dict>class _KeyCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::key_type>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [_KeyCollection](./_keycollection/)(const typename Dict::Ptr\&) | Initializes collection referencing specified dictionary. |
| [Contains](./contains/)(const TKey\&) const override | Checks if item is present in container. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator iterating through keys. |
| [idx_get](./idx_get/)(int) const override | Implements [IList](../ilist/) method. Not supported. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [TKey](./tkey/) | Key type. |

## See Also

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
