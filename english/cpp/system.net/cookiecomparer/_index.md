---
title: System::Net::CookieComparer class
linktitle: CookieComparer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CookieComparer class. Used to compare the Cookie class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.net/cookiecomparer/
---
## CookieComparer class


Used to compare the [Cookie](../cookie/) class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CookieComparer : public System::Collections::Generic::IComparer<System::SharedPtr<System::Net::Cookie>>
```

## Methods

| Method | Description |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Compares the specified objects. |
| static [get_Instance](./get_instance/)() | RTTI information. |
## See Also

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
