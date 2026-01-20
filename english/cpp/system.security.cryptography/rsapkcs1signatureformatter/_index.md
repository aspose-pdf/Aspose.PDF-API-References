---
title: System::Security::Cryptography::RSAPKCS1SignatureFormatter class
linktitle: RSAPKCS1SignatureFormatter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSAPKCS1SignatureFormatter class. Signs data with an RSA PKCS #1 v1.5 signature. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3800
url: /cpp/system.security.cryptography/rsapkcs1signatureformatter/
---
## RSAPKCS1SignatureFormatter class


Signs data with an [RSA](../rsa/) PKCS #1 v1.5 signature. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RSAPKCS1SignatureFormatter : public System::Security::Cryptography::AsymmetricSignatureFormatter
```

## Methods

| Method | Description |
| --- | --- |
| [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) override | Signs data. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)() | RTTI information. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)(const System::SharedPtr\<AsymmetricAlgorithm\>\&) | Constructor. |
| [SetHashAlgorithm](./sethashalgorithm/)(System::String) override | Sets hash algorithm to use. |
| [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) override | Sets key value. Not implemented. |
| [~RSAPKCS1SignatureFormatter](./~rsapkcs1signatureformatter/)() | Destructor. |
## See Also

* Class [AsymmetricSignatureFormatter](../asymmetricsignatureformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
