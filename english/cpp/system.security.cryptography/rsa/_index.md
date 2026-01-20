---
title: System::Security::Cryptography::RSA class
linktitle: RSA
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA class. Base class for implementations of RSA algorithm. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3400
url: /cpp/system.security.cryptography/rsa/
---
## RSA class


Base class for implementations of [RSA](./) algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)() | Creates default [RSA](./) aglorithm implementation. |
| static [Create](./create/)(const String\&) | Creates default [RSA](./) algorithm implementation. |
| static [Create](./create/)(int32_t) | Creates default [RSA](./) algorithm implementation with specifed key size. |
| static [Create](./create/)(const RSAParameters\&) | Creates default [RSA](./) algorithm implementation with specifed parameters. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Creates default [RSA](./) algorithm implementation with specifed XML-encoded parameters. |
| virtual [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Decrypts input data using the specified padding mode. |
| virtual [DecryptValue](./decryptvalue/)(ByteArrayPtr) | Decrypts value using private key. |
| virtual [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Encrypts input data using the specified padding mode. |
| virtual [EncryptValue](./encryptvalue/)(ByteArrayPtr) | Encrypts value using private key. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exports all parameters. |
| [FromXmlString](./fromxmlstring/)(String) override | Initializes object using XML-encoded parameters. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | RTTI information. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Gets signature algorithm associated with CSP object. |
| virtual [ImportParameters](./importparameters/)(RSAParameters) | Imports all parameters from data structure. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Computes the hash value of the specified data array using the specified hash algorithm and padding, and signs the result. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Computes the hash value of the specified data array using the specified hash algorithm and padding, and signs the result. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Computes the hash value of the specified binary stream using the specified hash algorithm and padding, and signs the result. |
| virtual [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) | Computes the signature for the specified hash value. |
| [ToXmlString](./toxmlstring/)(bool) override | Exports all parameters in XML format. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifies that the signature of the specified binary stream is valid. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) | Verifies that the signature of the specified hash is valid. |
## See Also

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
