---
title: System::Security::Cryptography::KeySizes class
linktitle: KeySizes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::KeySizes class. Set of key sizes accepted by symmetric algorithms. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2200
url: /cpp/system.security.cryptography/keysizes/
---
## KeySizes class


Set of key sizes accepted by symmetric algorithms. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class KeySizes : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_MaxSize](./get_maxsize/)() const | Gets maximal valid key size. |
| [get_MinSize](./get_minsize/)() const | Gets minimal valid key size. |
| [get_SkipSize](./get_skipsize/)() const | Gets valid key size step. |
| [KeySizes](./keysizes/)(int, int, int) | RTTI information. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
