---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt метод"
linktitle: "Decrypt"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt метод. Расшифровывает входные данные, используя указанный режим заполнения в C++."
type: docs
weight: 200
url: /ru/cpp/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Расшифровывает входные данные, используя указанный режим заполнения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
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
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Расшифровывает сообщение. Не реализовано.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Данные](../../../system.data/) для расшифровки. |
| use_oaep | bool | True, чтобы использовать паддинг OAEP, false, чтобы использовать паддинг PKCS#1 v1.5. |

### ReturnValue

Массив расшифрованных данных.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
