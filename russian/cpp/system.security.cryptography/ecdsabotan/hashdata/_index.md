---
title: "метод System::Security::Cryptography::ECDsaBotan::HashData"
linktitle: "HashData"
second_title: "Справочник API Aspose.PDF для C++"
description: "метод System::Security::Cryptography::ECDsaBotan::HashData. Вычисляет хеш-значение указанного массива данных, используя указанный алгоритм хеширования в C++."
type: docs
weight: 700
url: /ru/cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Вычисляет хеш‑значение указанного массива данных с использованием указанного алгоритма хеширования.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| data | ByteArrayPtr | [Data](../../../system.data/) для хеширования. |
| смещение | int32_t | Смещение в **data**. |
| count | int32_t | Количество байтов для хеширования. |
| hash_algorithm | HashAlgorithmName | Алгоритм хеширования. |

### ReturnValue

Хешированные данные.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Вычисляет хеш‑значение указанного бинарного потока с использованием указанного алгоритма хеширования.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | StreamPtr | Бинарный поток для хеширования. |
| hash_algorithm | HashAlgorithmName | Алгоритм хеширования. |

### ReturnValue

Хешированные данные.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
