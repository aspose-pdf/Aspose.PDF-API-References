---
title: System::Collections::Generic::SimpleEnumerator class
linktitle: SimpleEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::SimpleEnumerator class. Iterator class for simple containers holding elements directly using rbegin() and rend() functions. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3900
url: /cpp/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator class


Iterator class for simple containers holding elements directly using rbegin() and rend() functions. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```


| Parameter | Description |
| --- | --- |
| Container | Container type to iterate through. |
| Element | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| [get_Current](./get_current/)() const override | Gets 'current' element. |
| [SimpleEnumerator](./simpleenumerator/)(Object::ptr, Container\&) | Creates simple iterator. |

## See Also

* Class [BaseEnumerator](../baseenumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
