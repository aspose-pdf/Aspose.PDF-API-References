---
title: System::Security::Cryptography::HMACSHA512 class
linktitle: HMACSHA512
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::HMACSHA512 class. Hash-based Message Authentication Code that uses the SHA512 hash function. Partialy implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1900
url: /cpp/system.security.cryptography/hmacsha512/
---
## HMACSHA512 class


Hash-based Message [Authentication](../../system.security.authentication/) Code that uses the [SHA512](../sha512/) hash function. Partialy implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HMACSHA512 : public System::Security::Cryptography::HashAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Calculates [HMAC](../hmac/). |
| [HMACSHA512](./hmacsha512/)() | Constructor. |
| [HMACSHA512](./hmacsha512/)(const System::ArrayPtr\<uint8_t\>\&) | Constructor. |
## See Also

* Class [HashAlgorithm](../hashalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
