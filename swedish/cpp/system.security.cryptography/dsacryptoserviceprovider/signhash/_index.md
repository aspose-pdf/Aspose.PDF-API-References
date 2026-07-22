---
title: "System::Security::Cryptography::DSACryptoServiceProvider::SignHash metod"
linktitle: "SignHash"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSACryptoServiceProvider::SignHash metod. Beräknar signaturen för angivet inmatningsvärde i C++."
type: docs
weight: 1600
url: /sv/cpp/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash method


Beräknar signaturen för det angivna inmatningsvärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Hashvärde för data som ska signeras. |
| str | const String\& | Identifierare för hash-algoritm som används för att skapa hashen. |

### ReturnValue

[DSA](../../dsa/) signature for specified data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
