---
title: System::Security::Cryptography::DSACryptoServiceProvider class
linktitle: DSACryptoServiceProvider
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSACryptoServiceProvider class. DSA algorithm in CSP form. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider class


[DSA](../dsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| [CreateSignature](./createsignature/)(ByteArrayPtr) override | Create [DSA](../dsa/) signature for the specified data. |
| [Dispose](./dispose/)() override | Frees data associated with object. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Constructor. Uses default parameters. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const DSAParameters\&) | Constructor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Constructor. Not implemented. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t) | Constructor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Constructor. Not implemented. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Exports blob with information on key. Not implemented. |
| [ExportParameters](./exportparameters/)(bool) override | Exports CSP parameters. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Gets a [CspKeyContainerInfo](../cspkeycontainerinfo/) object. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Checks key exchange algorithm associated with object. |
| [get_KeySize](./get_keysize/)() override | Gets key size. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Checks whether key is persisted in CSP object. |
| [get_PublicOnly](./get_publiconly/)() const | Checks if public key only is present in CSP object. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Gets signature algorithm to use. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Checks whether the key persists in machine store instead of user store. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Imports blob with information on key. Not implemented. |
| [ImportParameters](./importparameters/)(DSAParameters) override | Imports all parameters from data structure. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Defines whether key is persisted in CSP object. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Defines whether the key persists in machine store instead of user store. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Computes the signature of specified input value. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&) | Computes the signature of specified input value. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Computes the signature of specified input value. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | RTTI information. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | RTTI information. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | RTTI information. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Computes the signature of specified input value. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Checks data signature. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified binary stream is valid. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Checks data signature. |
| [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) override | Verify [DSA](../dsa/) signature for the specified data. |
## See Also

* Class [DSA](../dsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
