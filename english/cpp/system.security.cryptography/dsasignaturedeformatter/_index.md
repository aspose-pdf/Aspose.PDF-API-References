---
title: System::Security::Cryptography::DSASignatureDeformatter class
linktitle: DSASignatureDeformatter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSASignatureDeformatter class. Used for verifying the DSA signatures. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.security.cryptography/dsasignaturedeformatter/
---
## DSASignatureDeformatter class


Used for verifying the [DSA](../dsa/) signatures. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSASignatureDeformatter : public System::Security::Cryptography::AsymmetricSignatureDeformatter
```

## Methods

| Method | Description |
| --- | --- |
| [DSASignatureDeformatter](./dsasignaturedeformatter/)() | Constructor. |
| [DSASignatureDeformatter](./dsasignaturedeformatter/)(const SharedPtr\<AsymmetricAlgorithm\>\&) | Constructor. |
| [SetHashAlgorithm](./sethashalgorithm/)(String) override | Sets hash algorithm to use. |
| [SetKey](./setkey/)(SharedPtr\<AsymmetricAlgorithm\>) override | Sets key to use for verification. |
| [VerifySignature](./verifysignature/)(ArrayPtr\<uint8_t\>, ArrayPtr\<uint8_t\>) override | Verifies the [DSA](../dsa/) signature of the specified hash. |
## See Also

* Class [AsymmetricSignatureDeformatter](../asymmetricsignaturedeformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
