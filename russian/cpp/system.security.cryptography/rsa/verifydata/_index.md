---
title: "System::Security::Cryptography::RSA::VerifyData method"
linktitle: "VerifyData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSA::VerifyData method. Проверяет, что подпись указанных данных действительна в C++."
type: docs
weight: 1300
url: /ru/cpp/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Подписанные данные. |
| подпись | const ByteArrayPtr\& | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| заполнение | const SharedPtr\<RSASignaturePadding\>\& | Режим заполнения. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Подписанные данные. |
| смещение | int32_t | Смещение в **data**. |
| count | int32_t | Количество байтов для хеширования. |
| подпись | const ByteArrayPtr\& | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| заполнение | const SharedPtr\<RSASignaturePadding\>\& | Режим заполнения. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Проверяет, что подпись указанного бинарного потока действительна.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const StreamPtr\& | Подписанные данные. |
| подпись | const ByteArrayPtr\& | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| заполнение | const SharedPtr\<RSASignaturePadding\>\& | Режим заполнения. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
