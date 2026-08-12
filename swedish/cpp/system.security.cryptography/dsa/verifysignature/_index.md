---
title: "System::Security::Cryptography::DSA::VerifySignature metod"
linktitle: "VerifySignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSA::VerifySignature metod. Verifiera DSA-signatur för den specificerade datan i C++."
type: docs
weight: 800
url: /sv/cpp/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature method


Verifiera [DSA](../) signatur för den specificerade datan.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | ByteArrayPtr | [Data](../../../system.data/) signerad med **rgb_signature**. |
| rgb_signature | ByteArrayPtr | [DSA](../) signatur. |

### ReturnValue

true - om **rgb_signature** matchar den [DSA](../) signatur som beräknats på **rgb_hash**, annars - false.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
