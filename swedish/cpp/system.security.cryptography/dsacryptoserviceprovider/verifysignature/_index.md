---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature metod"
linktitle: "VerifySignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature metod. Verifiera DSA-signatur för den angivna datan i C++."
type: docs
weight: 1900
url: /sv/cpp/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature method


Verifiera [DSA](../../dsa/) signatur för den angivna datan.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | ByteArrayPtr | [Data](../../../system.data/) signerad med **rgb_signature**. |
| rgb_signature | ByteArrayPtr | [DSA](../../dsa/) signatur. |

### ReturnValue

sant - om **rgb_signature** matchar den [DSA](../../dsa/) signatur som beräknats på **rgb_hash**, annars - falskt.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
