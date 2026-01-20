---
title: System::Security::Cryptography::TripleDESManaged class
linktitle: TripleDESManaged
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::TripleDESManaged class. Managed TripleDES implementation. Only supports ECB and CFB modes with None padding and CBC mode with None, Zeros and PKCS7 paddings. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 5200
url: /cpp/system.security.cryptography/tripledesmanaged/
---
## TripleDESManaged class


Managed [TripleDES](../tripledes/) implementation. Only supports ECB and CFB modes with None padding and CBC mode with None, Zeros and PKCS7 paddings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TripleDESManaged : public System::Security::Cryptography::TripleDES
```

## Methods

| Method | Description |
| --- | --- |
| [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Creates decryptor object with explicit parameters. |
| virtual [CreateDecryptor](./createdecryptor/)() | Creates decryptor object with parameters defined by algorithm object. |
| [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Creates encryptor object with explicit parameters. |
| virtual [CreateEncryptor](./createencryptor/)() | Creates encryptor object with parameters defined by algorithm object. |
| [GenerateIV](./generateiv/)() override | Creates random initial value and stores it in algorithm's internals. |
| [GenerateKey](./generatekey/)() override | Creates random key and stores it in algorithm's internals. |
## See Also

* Class [TripleDES](../tripledes/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
