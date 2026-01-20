---
title: System::Collections::Generic::BaseEnumerator class
linktitle: BaseEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::BaseEnumerator class. Enumerator definition to wrap STL-styled types for C#-styled usage. Makes no assertions on container structure except for existance of sequental iterator. Uses begin() and end() functions. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.collections.generic/baseenumerator/
---
## BaseEnumerator class


[Enumerator](../baseset/) definition to wrap STL-styled types for C#-styled usage. Makes no assertions on container structure except for existance of sequental iterator. Uses begin() and end() functions. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class BaseEnumerator : public System::Collections::Generic::IEnumerator<Element>
```


| Parameter | Description |
| --- | --- |
| Container | STL-styled container type. |
| Element | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [BaseEnumerator](./baseenumerator/)(const Object::ptr\&, Container\&) | Initializes iterator. |
| [IsValid](./isvalid/)() const | Checks whether [MoveNext()](./movenext/) was called and end was not reached. |
| [MoveNext](./movenext/)() override | Enumerator-style increment. |
| [Reset](./reset/)() override | Resets enumerator to allow re-enumerating elements. |

## See Also

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
