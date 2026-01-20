---
title: System::Security::Cryptography::ECDsa class
linktitle: ECDsa
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsa class. Base class for implementations of ECDsa algorithm. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.security.cryptography/ecdsa/
---
## ECDsa class


Base class for implementations of [ECDsa](./) algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)() | Creates default ECDSA aglorithm implementation. |
| static [Create](./create/)(const ECCurve\&) | Creates default ECDSA aglorithm implementation with newly created key over the specified curve. |
| static [Create](./create/)(const ECParameters\&) | Creates default ECDSA aglorithm implementation using the specified parameters. |
| static [Create](./create/)(const String\&) | Creates specified ECDSA aglorithm implementation. |
| virtual [ExportExplicitParameters](./exportexplicitparameters/)(bool) | Exports explicit parameters. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exports named or explicit parameters. |
| virtual [GenerateKey](./generatekey/)(const ECCurve\&) | Generates a new public/private key pair for the specified curve. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | RTTI information. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Gets signature algorithm to use. |
| virtual [ImportParameters](./importparameters/)(const ECParameters\&) | Imports all parameters from data structure. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Computes the hash value of the specified data array using the specified hash algorithm, and signs the result. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Computes the hash value of the specified data array using the specified hash algorithm, and signs the result. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Computes the hash value of the specified binary stream using the specified hash algorithm, and signs the result. |
| virtual [SignHash](./signhash/)(const ByteArrayPtr\&) | Computes the signature of specified input value. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified binary stream is valid. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) | Checks data signature. |
## See Also

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
