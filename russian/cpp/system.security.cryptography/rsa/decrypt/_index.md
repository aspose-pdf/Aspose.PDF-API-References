---
title: "System::Security::Cryptography::RSA::Decrypt метод"
linktitle: "Decrypt"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Security::Cryptography::RSA::Decrypt. Расшифровывает входные данные, используя указанный режим заполнения в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt method


Расшифровывает входные данные, используя указанный режим заполнения.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| data | ByteArrayPtr | Массив [Byte](../../../system/byte/) для расшифровки. |
| заполнение | SharedPtr\<RSAEncryptionPadding\> | Режим padding. |

### ReturnValue

Расшифрованные данные в формате массива байтов.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
