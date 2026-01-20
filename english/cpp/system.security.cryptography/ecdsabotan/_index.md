---
title: System::Security::Cryptography::ECDsaBotan class
linktitle: ECDsaBotan
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsaBotan class. ECDsa algorithm in Botan form. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1400
url: /cpp/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan class


[ECDsa](../ecdsa/) algorithm in Botan form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## Methods

| Method | Description |
| --- | --- |
| [ECDsaBotan](./ecdsabotan/)() | Constructor. Uses default parameters. |
| [ECDsaBotan](./ecdsabotan/)(const ECParameters\&) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(const ECCurve\&) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(int32_t) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | Constructor. |
| [ExportExplicitParameters](./exportexplicitparameters/)(bool) override | Exports explicit parameters. |
| [ExportParameters](./exportparameters/)(bool) override | Exports named or explicit parameters. |
| [FromXmlString](./fromxmlstring/)(String) override | Initializes object using XML-encoded parameters. Not implemented. |
| [FromXmlString](./fromxmlstring/)(const String\&, ECKeyXmlFormat) | Initializes object using XML-encoded parameters. Not implemented. |
| [GenerateKey](./generatekey/)(const ECCurve\&) override | Generates a new public/private key pair for the specified curve. |
| [get_HashAlgorithm](./get_hashalgorithm/)() const | Gets hash algortihm. |
| [HashData](./hashdata/)(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) override | Computes the hash value of the specified data array using the specified hash algorithm. |
| [HashData](./hashdata/)(StreamPtr, HashAlgorithmName) override | Computes the hash value of the specified binary stream using the specified hash algorithm. |
| [ImportParameters](./importparameters/)(const ECParameters\&) override | Imports all parameters from data structure. |
| [set_HashAlgorithm](./set_hashalgorithm/)(const HashAlgorithmName\&) | Sets hash algortihm. |
| [set_KeySize](./set_keysize/)(int32_t) override | Sets key size. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Computes the hash value of the specified data array, and signs the result. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Computes the hash value of the specified data array, and signs the result. |
| [SignData](./signdata/)(const StreamPtr\&) | Computes the hash value of the specified binary stream, and signs the result. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | RTTI information. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | RTTI information. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | RTTI information. |
| [SignHash](./signhash/)(const ByteArrayPtr\&) override | Computes the signature of specified input value. |
| [ToXmlString](./toxmlstring/)(bool) override | Exports all parameters in XML format. Not implemented. |
| [ToXmlString](./toxmlstring/)(ECKeyXmlFormat) | Exports all parameters in XML format. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&) | Verifies that the signature of the specified binary stream is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified binary stream is valid. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) override | Checks data signature. |
## See Also

* Class [ECDsa](../ecdsa/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
