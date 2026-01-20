---
title: System::Security::Cryptography::AsymmetricAlgorithm class
linktitle: AsymmetricAlgorithm
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::AsymmetricAlgorithm class. Abstract base class for asymmetric encryption algorithms. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.security.cryptography/asymmetricalgorithm/
---
## AsymmetricAlgorithm class


Abstract base class for asymmetric encryption algorithms. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AsymmetricAlgorithm : public virtual System::Object,
                            public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Clear](./clear/)() | Releases all resources. |
| static [Create](./create/)() | Creates a default algorithm. Not implemented. |
| static [Create](./create/)(const String\&) | Creates algorithm by name. Not implemented. |
| [Dispose](./dispose/)() override | Releases resources owned by the current object. |
| virtual [FromXmlString](./fromxmlstring/)(String) | Reads algorithm parameters from XML string. |
| virtual [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() | Gets key exchange algorithm to use. |
| virtual [get_KeySize](./get_keysize/)() | RTTI information. |
| virtual [get_LegalKeySizes](./get_legalkeysizes/)() | Gets array of allowed key sizes. |
| virtual [get_SignatureAlgorithm](./get_signaturealgorithm/)() | Gets signature algorithm to use. |
| virtual [set_KeySize](./set_keysize/)(int32_t) | Sets key size. |
| virtual [ToXmlString](./toxmlstring/)(bool) | Writes algorithm parameters to XML string. |
## See Also

* Class [Object](../../system/object/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
