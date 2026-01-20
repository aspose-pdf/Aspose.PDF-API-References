---
title: System::Collections::ObjectModel::ReadOnlyCollection class
linktitle: ReadOnlyCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::ObjectModel::ReadOnlyCollection class. Wraps specific container to access it in read-only mode. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.collections.objectmodel/readonlycollection/
---
## ReadOnlyCollection class


Wraps specific container to access it in read-only mode. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class ReadOnlyCollection : public virtual System::Object,
                                               public System::Collections::Generic::IList<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [Contains](./contains/)(const T\&) const override | Checks if container contains specific item. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Copies container elements to existing array elements. |
| [get_Count](./get_count/)() const override | Gets count of container elements. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Checks if collection is read only. |
| [GetEnumerator](./getenumerator/)() override | Gets collection enumerator. |
| [idx_get](./idx_get/)(int) const override | Gets item at specific position. |
| [IndexOf](./indexof/)(const T\&) const override | Looks for specific item in collection. |
| [ReadOnlyCollection](./readonlycollection/)(const SharedPtr\<Generic::IList\<T\>\>\&) | Wraps read-only collection around specific collection. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Does nothing as read-only collection only wraps data and stores nothing. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Implemented interface. |
| [IEnumeratorPtr](./ienumeratorptr/) | Container of same elements. |
| [ValueType](./valuetype/) | Value type. |

## See Also

* Class [Object](../../system/object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
