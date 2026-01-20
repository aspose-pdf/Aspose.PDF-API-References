---
title: System::Security::Cryptography::DSA class
linktitle: DSA
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSA class. Base class for implementations of DSA algorithm. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.security.cryptography/dsa/
---
## DSA class


Base class for implementations of [DSA](./) algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)() | Creates default [DSA](./) aglorithm implementation. |
| static [Create](./create/)(const String\&) | Creates default [DSA](./) algorithm implementation. |
| static [Create](./create/)(int32_t) | Creates default [DSA](./) algorithm implementation with specifed key size. |
| static [Create](./create/)(const DSAParameters\&) | Creates default [DSA](./) algorithm implementation with specifed parameters. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Creates default [DSA](./) algorithm implementation with specifed XML-encoded parameters. |
| virtual [CreateSignature](./createsignature/)(ByteArrayPtr) | RTTI information. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exports all parameters. |
| [FromXmlString](./fromxmlstring/)(String) override | Initializes object using XML-encoded parameters. |
| virtual [ImportParameters](./importparameters/)(DSAParameters) | Imports all parameters from data structure. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Computes the hash value of the specified data array using the specified hash algorithm, and signs the result. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Computes the hash value of the specified data array using the specified hash algorithm, and signs the result. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Computes the hash value of the specified binary stream using the specified hash algorithm, and signs the result. |
| [ToXmlString](./toxmlstring/)(bool) override | Exports all parameters in XML format. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified data is valid. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifies that the signature of the specified binary stream is valid. |
| virtual [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) | Verify [DSA](./) signature for the specified data. |
## See Also

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
