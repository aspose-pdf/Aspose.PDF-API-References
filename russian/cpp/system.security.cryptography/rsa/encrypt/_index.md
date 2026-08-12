---
title: "Метод System::Security::Cryptography::RSA::Encrypt"
linktitle: "Шифровать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Security::Cryptography::RSA::Encrypt. Шифрует входные данные, используя указанный режим заполнения в C++."
type: docs
weight: 300
url: /ru/cpp/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt method


Шифрует входные данные, используя указанный режим заполнения.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| data | ByteArrayPtr | Массив [Byte](../../../system/byte/) для шифрования. |
| заполнение | SharedPtr\<RSAEncryptionPadding\> | Режим padding. |

### ReturnValue

Зашифрованные данные в формате массива байтов.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
