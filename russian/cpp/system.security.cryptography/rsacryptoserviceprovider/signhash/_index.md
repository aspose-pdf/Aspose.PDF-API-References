---
title: "System::Security::Cryptography::RSACryptoServiceProvider::SignHash метод"
linktitle: "SignHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::SignHash метод. Вычисляет подпись для указанного значения хеша в C++."
type: docs
weight: 1700
url: /ru/cpp/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method


Вычисляет подпись для указанного хеш-значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| хеш | ByteArrayPtr | Значение хэша. |
| hash_algorithm | HashAlgorithmName | Алгоритм хеширования. |
| padding | SharedPtr\<RSASignaturePadding\> | Режим заполнения. возвращает подпись [RSA](../../rsa/) для указанного хеша. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method


Вычисляет подпись указанного входного значения. Не реализовано.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Хеш-значение данных для подписи. |
| str | const String\& | Идентификатор алгоритма хеширования, используемый для создания хеша. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
