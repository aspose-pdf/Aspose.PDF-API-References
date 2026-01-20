---
title: System::Collections::Concurrent::ConcurrentDictionary class
linktitle: ConcurrentDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Concurrent::ConcurrentDictionary class. Thread-safe dictionary implementation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary class


Thread-safe dictionary implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const TKey\&, const TValue\&) override | Adds value into dictionary. |
| [Clear](./clear/)() override | Deletes all elements in container. |
| [CopyTo](./copyto/)(ArrayPtr\<System::Collections::Generic::KeyValuePair\<TKey, TValue\>\>, int) override | Copies container elements to existing array elements. |
| [get_KeysInternal](./get_keysinternal/)() const override | Gets wrapper collection to access dictionary keys. |
| [idx_set](./idx_set/)(const TKey\&, TValue) override | RTTI information. |
| [Remove](./remove/)(const TKey\&) override | Removes element from container. |
| [TryAdd](./tryadd/)(const TKey\&, const TValue\&) | Tries to add key/value pair into the dictionary. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Implementation type. |
| [ThisType](./thistype/) | This type. |
## Remarks



```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // Create the ConcurrentDictionary-class instance.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // Fill the concurrent dictionary.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
This code example produces the following output:
9
*/
```

## See Also

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Concurrent](../)
* Library [Aspose.PDF for C++](../../)
