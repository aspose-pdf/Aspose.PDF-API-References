---
title: "System::Security::Cryptography::RSACryptoServiceProvider::SignData метод"
linktitle: "SignData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::SignData метод. Вычисляет подпись указанного входного значения в C++."
type: docs
weight: 1600
url: /ru/cpp/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Buffer](../../../system/buffer/) для чтения входных данных. |
| halg | const SharedPtr\<Object\>\& | Алгоритм хеширования для использования. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Buffer](../../../system/buffer/) для чтения входных данных. |
| смещение | int32_t | Начальный индекс фрагмента входного буфера. |
| count | int32_t | Размер фрагмента входного буфера. |
| halg | const SharedPtr\<Object\>\& | Алгоритм хеширования для использования. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input_stream | const SharedPtr\<IO::Stream\>\& | Поток для чтения данных, которые подписываются. |
| halg | const SharedPtr\<Object\>\& | Алгоритм хеширования для использования. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
