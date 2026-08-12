---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData метод"
linktitle: "VerifyData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData метод. Проверяет подпись данных в C++."
type: docs
weight: 1700
url: /ru/cpp/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) для проверки подписи. |
| подпись | const ByteArrayPtr\& | Подпись как получена. |

### ReturnValue

Истина, если подпись действительна, иначе ложь.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Подписанные данные. |
| подпись | const ByteArrayPtr\& | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. Возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Проверяет, что подпись указанных данных действительна.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Подписанные данные. |
| смещение | int32_t | Смещение в **data**. |
| count | int32_t | Количество байтов для хеширования. |
| подпись | const ByteArrayPtr\& | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. Возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Проверяет, что подпись указанного бинарного потока действительна.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const StreamPtr\& | Подписанные данные. |
| подпись | const ByteArrayPtr\& | Данные подписи. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. Возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
