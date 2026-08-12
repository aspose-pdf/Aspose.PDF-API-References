---
title: "System::Security::Cryptography::RSA::SignData method"
linktitle: "SignData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSA::SignData method. Вычисляет хеш-значение указанного массива данных с использованием заданного алгоритма хеширования и заполнения, и подписывает результат в C++."
type: docs
weight: 1000
url: /ru/cpp/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Вычисляет хеш-значение указанного массива данных, используя указанный хеш-алгоритм и заполнение, и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Входной массив данных. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Режим заполнения. возвращает подпись [RSA](../) для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Вычисляет хеш-значение указанного массива данных, используя указанный хеш-алгоритм и заполнение, и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Входной массив данных. |
| смещение | int32_t | Смещение в **data**. |
| count | int32_t | Количество байтов, используемых в качестве входных данных. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Режим заполнения. возвращает подпись [RSA](../) для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Вычисляет хеш-значение указанного бинарного потока, используя указанный хеш-алгоритм и заполнение, и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const StreamPtr\& | Бинарный поток. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Режим заполнения. возвращает подпись [RSA](../) для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
