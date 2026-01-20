---
title: System::Collections::Generic::ReverseEnumerator class
linktitle: ReverseEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::ReverseEnumerator class. Enumerator that reverse-iterates through container. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3800
url: /cpp/system.collections.generic/reverseenumerator/
---
## ReverseEnumerator class


[Enumerator](../baseset/) that reverse-iterates through container. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class ReverseEnumerator : public System::Collections::Generic::IEnumerator<typename Container::value_type>
```


| Parameter | Description |
| --- | --- |
| Container | Container to iterate through. |
| Element | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [get_Current](./get_current/)() const override | Gets 'current' element. |
| [IsValid](./isvalid/)() const | Checks whether [MoveNext()](./movenext/) was called and end was not reached. |
| [MoveNext](./movenext/)() override | Enumerator-style increment. |
| [Reset](./reset/)() override | Resets enumerator to allow re-enumerating elements. |
| [ReverseEnumerator](./reverseenumerator/)(const Object::ptr\&, Container\&) | Initializes iterator. |
| virtual [~ReverseEnumerator](./~reverseenumerator/)() | Destructor. |

## See Also

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
