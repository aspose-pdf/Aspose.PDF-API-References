---
title: System::Security::Cryptography::DSA::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSA::VerifySignature method. Verify DSA signature for the specified data in C++.'
type: docs
weight: 800
url: /cpp/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature method


Verify [DSA](../) signature for the specified data.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | ByteArrayPtr | [Data](../../../system.data/) signed with **rgb_signature**. |
| rgb_signature | ByteArrayPtr | [DSA](../) signature. |

### ReturnValue

true - if **rgb_signature** matches the [DSA](../) signature computed on **rgb_hash**, otherwise - false.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
