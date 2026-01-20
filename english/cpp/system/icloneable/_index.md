---
title: System::ICloneable class
linktitle: ICloneable
second_title: Aspose.PDF for C++ API Reference
description: 'System::ICloneable class. Defies a method that enables object cloning - creating a copy of an object. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3200
url: /cpp/system/icloneable/
---
## ICloneable class


Defies a method that enables object cloning - creating a copy of an object. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICloneable : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Clone](./clone/)() | RTTI information. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
