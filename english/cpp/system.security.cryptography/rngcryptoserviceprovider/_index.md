---
title: System::Security::Cryptography::RNGCryptoServiceProvider class
linktitle: RNGCryptoServiceProvider
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RNGCryptoServiceProvider class. Radom number generator that follows CSP notion. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3300
url: /cpp/system.security.cryptography/rngcryptoserviceprovider/
---
## RNGCryptoServiceProvider class


Radom number generator that follows CSP notion. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RNGCryptoServiceProvider : public System::Security::Cryptography::RandomNumberGenerator
```

## Methods

| Method | Description |
| --- | --- |
| [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) override | Fills existing array elements with random bytes. |
| [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) override | Fills existing array view elements with random bytes. |
| [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) override | Fills existing array elements with random non-zero bytes. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) override | Fills existing array view elements with random non-zero bytes. |
| [RNGCryptoServiceProvider](./rngcryptoserviceprovider/)() | Constructor. |
| virtual [~RNGCryptoServiceProvider](./~rngcryptoserviceprovider/)() | Destructor. |
## See Also

* Class [RandomNumberGenerator](../randomnumbergenerator/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
