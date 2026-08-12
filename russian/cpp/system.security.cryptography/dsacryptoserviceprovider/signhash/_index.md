---
title: "System::Security::Cryptography::DSACryptoServiceProvider::SignHash метод"
linktitle: "SignHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::SignHash метод. Вычисляет подпись указанного входного значения в C++."
type: docs
weight: 1600
url: /ru/cpp/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash method


Вычисляет подпись указанного входного значения.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Хеш-значение данных для подписи. |
| str | const String\& | Идентификатор алгоритма хеширования, используемый для создания хеша. |

### ReturnValue

[DSA](../../dsa/) signature for specified data.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
