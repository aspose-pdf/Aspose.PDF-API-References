---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature метод"
linktitle: "VerifySignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature метод. Проверяет DSA подпись для указанных данных в C++."
type: docs
weight: 1900
url: /ru/cpp/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature method


Проверьте подпись [DSA](../../dsa/) для указанных данных.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | ByteArrayPtr | [Data](../../../system.data/) подписаны с помощью **rgb_signature**. |
| rgb_signature | ByteArrayPtr | Подпись [DSA](../../dsa/). |

### ReturnValue

true — если **rgb_signature** совпадает с подписью [DSA](../../dsa/), вычисленной по **rgb_hash**, иначе — false.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
