---
title: "System::Security::Cryptography::DSA::SignData метод"
linktitle: "SignData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::DSA::SignData метод. Вычисляет хеш-значение указанного массива данных с использованием указанного алгоритма хеширования и подписывает результат в C++."
type: docs
weight: 500
url: /ru/cpp/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Вычисляет хеш-значение указанного массива данных с использованием указанного хеш-алгоритма и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Входной массив данных. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. Возвращает подпись [DSA](../) для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Вычисляет хеш-значение указанного массива данных с использованием указанного хеш-алгоритма и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | const ByteArrayPtr\& | Входной массив данных. |
| смещение | int32_t | Смещение в **data**. |
| count | int32_t | Количество байтов, используемых в качестве входных данных. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. Возвращает подпись [DSA](../) для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Вычисляет хеш-значение указанного бинарного потока с использованием указанного хеш-алгоритма и подписывает результат.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const StreamPtr\& | Бинарный поток. |
| hash_algorithm | const HashAlgorithmName\& | Алгоритм хеширования. Возвращает подпись [DSA](../) для входных данных. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
