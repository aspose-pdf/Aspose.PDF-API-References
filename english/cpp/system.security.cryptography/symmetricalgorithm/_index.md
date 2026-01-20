---
title: System::Security::Cryptography::SymmetricAlgorithm class
linktitle: SymmetricAlgorithm
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::SymmetricAlgorithm class. Symmetric algorithm using same key for encryption and decryption base class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 4900
url: /cpp/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm class


Symmetric algorithm using same key for encryption and decryption base class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)(const String\&) | Creates algorithm instance. |
| virtual [CreateDecryptor](./createdecryptor/)() | Creates decryptor with parameters associated with algorithm object. |
| virtual [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Creates decryptor with explicit parameters. |
| virtual [CreateEncryptor](./createencryptor/)() | Creates encryptor with parameters associated with algorithm object. |
| virtual [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Creates encryptor with explicit parameters. |
| virtual [GenerateIV](./generateiv/)() | Generates random initial value for the algorithm. Overrides existing one (if any). |
| virtual [GenerateKey](./generatekey/)() | Generates random key for the algorithm. Overrides existing one (if any). |
| virtual [get_BlockSize](./get_blocksize/)() | Gets block size of cryptographic operation. |
| virtual [get_FeedbackSize](./get_feedbacksize/)() | Gets feedback size of cryptographic operation. |
| virtual [get_IV](./get_iv/)() | Gets initial value of cryptographic operation. Creates new if not created yet. |
| virtual [get_Key](./get_key/)() | Gets key of cryptographic operation. Creates new if not created yet. |
| virtual [get_KeySize](./get_keysize/)() | Gets key size of cryptographic operation. |
| virtual [get_Mode](./get_mode/)() | Gets mode of cryptographic operation. |
| virtual [get_Padding](./get_padding/)() | Gets padding of cryptographic operation. |
| virtual [set_BlockSize](./set_blocksize/)(int) | Sets block size of cryptographic operation. |
| virtual [set_FeedbackSize](./set_feedbacksize/)(int) | Sets feedback size of cryptographic operation. |
| virtual [set_IV](./set_iv/)(System::ArrayPtr\<uint8_t\>) | Sets initial value of cryptographic operation. |
| virtual [set_Key](./set_key/)(System::ArrayPtr\<uint8_t\>) | Sets key of cryptographic operation. |
| virtual [set_KeySize](./set_keysize/)(int) | Sets key size of cryptographic operation. |
| virtual [set_Mode](./set_mode/)(CipherMode) | Sets mode of cryptographic operation. |
| virtual [set_Padding](./set_padding/)(PaddingMode) | Sets padding of cryptographic operation. |
| [ValidKeySize](./validkeysize/)(int) | Checks if key size is valid. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
