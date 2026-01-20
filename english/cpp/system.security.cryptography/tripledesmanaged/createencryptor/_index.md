---
title: System::Security::Cryptography::TripleDESManaged::CreateEncryptor method
linktitle: CreateEncryptor
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::TripleDESManaged::CreateEncryptor method. Creates encryptor object with parameters defined by algorithm object in C++.'
type: docs
weight: 200
url: /cpp/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor() method


Creates encryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Creates encryptor object with explicit parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Encryption key in byte array form. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initial value in byte array form. |

### ReturnValue

Newly created encryptor object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
