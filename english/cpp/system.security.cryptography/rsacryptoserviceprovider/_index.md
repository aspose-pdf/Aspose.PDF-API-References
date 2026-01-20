---
title: System::Security::Cryptography::RSACryptoServiceProvider class
linktitle: RSACryptoServiceProvider
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSACryptoServiceProvider class. RSA algorithm in CSP form. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3500
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider class


[RSA](../rsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| [Decrypt](./decrypt/)(const ByteArrayPtr\&, bool) | Decrypts message. Not implemented. |
| [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Decrypts input data using the specified padding mode. |
| [Dispose](./dispose/)() override | Frees data associated with object. |
| [Encrypt](./encrypt/)(const ByteArrayPtr\&, bool) | Encrypts message. Not implemented. |
| [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Encrypts input data using the specified padding mode. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Exports blob with information on key. Not implemented. |
| [ExportParameters](./exportparameters/)(bool) override | Exports CSP parameters. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Gets a [CspKeyContainerInfo](../cspkeycontainerinfo/) object. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Checks key exchange algorithm associated with object. |
| [get_KeySize](./get_keysize/)() override | Gets key size used by algorithm. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Checks whether key is persisted in CSP object. |
| [get_PublicOnly](./get_publiconly/)() const | Checks if public key only is present in CSP object. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Gets signature algorithm associated with CSP object. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Checks whether the key persists in machine store instead of user store. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Imports blob with information on key. Not implemented. |
| [ImportParameters](./importparameters/)(RSAParameters) override | Imports CSP parameters. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | RTTI information. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Constructor. Not implemented. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const RSAParameters\&) | Constructor. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t) | Constructor. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Constructor. Not implemented. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Defines whether key is persisted in CSP object. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Defines whether the key persists in machine store instead of user store. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) | Computes the signature of specified input value. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) | Computes the signature of specified input value. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) | Computes the signature of specified input value. |
| [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) override | Computes the signature for the specified hash value. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Computes the signature of specified input value. Not implemented. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) | Checks data signature. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Checks data signature. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) override | Verifies that the signature of the specified hash is valid. |
## See Also

* Class [RSA](../rsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
