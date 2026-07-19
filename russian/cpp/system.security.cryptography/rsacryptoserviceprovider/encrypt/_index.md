---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt метод"
linktitle: "Шифровать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt метод. Шифрует входные данные, используя указанный режим паддинга в C++."
type: docs
weight: 400
url: /ru/cpp/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Шифрует входные данные, используя указанный режим заполнения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
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
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Шифрует сообщение. Не реализовано.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) для шифрования. |
| use_oaep | bool | True, чтобы использовать паддинг OAEP, false, чтобы использовать паддинг PKCS#1 v1.5. |

### ReturnValue

Массив зашифрованных данных.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
