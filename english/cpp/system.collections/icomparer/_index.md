---
title: System::Collections::IComparer class
linktitle: IComparer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IComparer class. Interface that compares two objects in greater-equal-less sense. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.collections/icomparer/
---
## IComparer class


Interface that compares two objects in greater-equal-less sense. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IComparer : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Compare](./compare/)(const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) const | RTTI information. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
