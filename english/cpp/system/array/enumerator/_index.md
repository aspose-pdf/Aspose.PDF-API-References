---
title: System::Array::Enumerator class
linktitle: Enumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Enumerator class. Implements IEnumerator interface that enables enumeration of elements of an Array object. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 6800
url: /cpp/system/array/enumerator/
---
## Enumerator class


Implements IEnumerator interface that enables enumeration of elements of an [Array](../) object. Objects of this class should only be allocated using [System::MakeObject()](../../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<T>
```

## Methods

| Method | Description |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<Array\<T\>\>\&) | Constructs a new [Enumerator](./) object that represents the specified array. |
| [get_Current](./get_current/)() const override | Returns a copy of the current element. |
| [MoveNext](./movenext/)() override | Checks if the current element's index does not point to the last element in the array and advances it if id does not. |
| [Reset](./reset/)() override | Resets the current element's index. |
| virtual [~Enumerator](./~enumerator/)() | Destructor. |
## See Also

* Class [Object](../../object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
