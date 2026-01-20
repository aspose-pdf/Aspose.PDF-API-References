---
title: System::Security::Cryptography::AsymmetricSignatureFormatter class
linktitle: AsymmetricSignatureFormatter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::AsymmetricSignatureFormatter class. Base class for assimetric signature formatters. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.security.cryptography/asymmetricsignatureformatter/
---
## AsymmetricSignatureFormatter class


Base class for assimetric signature formatters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AsymmetricSignatureFormatter : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) | RTTI information. |
| virtual [CreateSignature](./createsignature/)(System::SharedPtr\<HashAlgorithm\>) | Creates the signature for the specified hash value. |
| virtual [SetHashAlgorithm](./sethashalgorithm/)(System::String) | Sets hash algorithm to use. |
| virtual [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) | Sets asymmetric algorithm to use when calculating the signature. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
