---
title: System::Security::Cryptography::Rfc2898DeriveBytes class
linktitle: Rfc2898DeriveBytes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::Rfc2898DeriveBytes class. Implements password-based key derivation, PBKDF2. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2900
url: /cpp/system.security.cryptography/rfc2898derivebytes/
---
## Rfc2898DeriveBytes class


Implements password-based key derivation, PBKDF2. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Rfc2898DeriveBytes : public System::Security::Cryptography::DeriveBytes
```

## Methods

| Method | Description |
| --- | --- |
| [GetBytes](./getbytes/)(int32_t) override | Fills existing array elements with pseudo-random key bytes. |
| [Reset](./reset/)() override |  |
| [Rfc2898DeriveBytes](./rfc2898derivebytes/)(ArrayPtr\<uint8_t\>, ArrayPtr\<uint8_t\>, int32_t) | RTTI information. |
## See Also

* Class [DeriveBytes](../derivebytes/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
