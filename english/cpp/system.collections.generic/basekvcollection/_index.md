---
title: System::Collections::Generic::BaseKVCollection class
linktitle: BaseKVCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::BaseKVCollection class. Holds common code for collections of keys or values. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.collections.generic/basekvcollection/
---
## BaseKVCollection class


Holds common code for collections of keys or values. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Dict,typename KV>class BaseKVCollection : public System::Collections::Generic::IKVCollection<KV>
```


| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) type. |
| KV | Key or value type, whichever the interface is used for. |
## Methods

| Method | Description |
| --- | --- |
| [BaseKVCollection](./basekvcollection/)(const typename Dict::Ptr\&) | Creates collection. |
| [CopyTo](./copyto/)(ArrayPtr\<KV\>, int) override | Copies data to existing array elements. |
| [get_Count](./get_count/)() const override | Gets number of elements. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Enables compilation, but doesn't actually do anything as this structure doesn't own data. |

## See Also

* Class [IKVCollection](../ikvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
