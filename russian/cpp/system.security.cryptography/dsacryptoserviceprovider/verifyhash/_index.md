---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash метод"
linktitle: "VerifyHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash метод. Проверяет подпись данных в C++."
type: docs
weight: 1800
url: /ru/cpp/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash method


Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
