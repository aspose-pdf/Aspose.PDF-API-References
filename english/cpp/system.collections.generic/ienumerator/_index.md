---
title: System::Collections::Generic::IEnumerator class
linktitle: IEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerator class. Interface of enumerator which can be used to iterate through some elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2300
url: /cpp/system.collections.generic/ienumerator/
---
## IEnumerator class


Interface of enumerator which can be used to iterate through some elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [AsVirtualizedIterator](./asvirtualizediterator/)() | Prepares the iterator to be used by the VirtualizedIterator class. |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| virtual [Current](./current/)() const | Gets current element. |
| virtual [get_Current](./get_current/)() const | Gets current element. |
| [IEnumerator](./ienumerator/)() |  |
| [IncrementIterator](./incrementiterator/)() override | Moves the iterator step forward. |
| [InitializeIterator](./initializeiterator/)() override | Does the first [MoveNext()](./movenext/) call and prepares the enumerator object to be used by VirtualizedIterator. |
| [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | Marks the enumerator owned by virtualized iterator. |
| virtual [MoveNext](./movenext/)() | Moves enumerator to the next element. If no element was referenced before, sets reference to the first element available. If container end was hit, does nothing. |
| virtual [Reset](./reset/)() | Resets enumerator to position before first element. |
| virtual [~IEnumerator](./~ienumerator/)() |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | Value type. |
## Remarks



```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Create the List-class instance.
  auto collection = MakeObject<List<int>>();

  // Fill the list.
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // Get the enumerator of the list.
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // Get the current element and print it.
    std::cout << enumerator->get_Current() << ' ';
  }

  // Reset the enumerator.
  enumerator->Reset();

  return 0;
}
/*
This code example produces the following output:
1 2 3
*/
```

## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
