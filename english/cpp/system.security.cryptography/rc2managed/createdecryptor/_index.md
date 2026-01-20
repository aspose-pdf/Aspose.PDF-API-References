---
title: System::Security::Cryptography::RC2Managed::CreateDecryptor method
linktitle: CreateDecryptor
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RC2Managed::CreateDecryptor method. Creates decryptor object with parameters defined by algorithm object in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor() method


Creates decryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Creates decryptor object with explicit parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Encryption key in byte array form. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initial value in byte array form. |

### ReturnValue

Newly created decryptor object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
