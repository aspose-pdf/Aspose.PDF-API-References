---
title: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash метод"
linktitle: "VerifyHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash метод. Проверяет, является ли подпись указанного хеша действительной в C++."
type: docs
weight: 1900
url: /ru/cpp/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Проверяет, что подпись указанного хеша действительна.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| хеш | ByteArrayPtr | Хеш-значение подписанных данных. |
| подпись | ByteArrayPtr | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| заполнение | SharedPtr\<RSASignaturePadding\> | Режим заполнения. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Хеш, рассчитанный для полученных данных. |
| str | const String\& | Имя используемого алгоритма хеширования. |
| rgb_signature | const ByteArrayPtr\& | Подпись как получена. |

### ReturnValue

Истина, если подпись действительна, иначе ложь.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
