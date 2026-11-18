---
title: System::Security::Cryptography::DSASignatureDeformatter::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSASignatureDeformatter::VerifySignature method. Verifies the DSA signature of the specified hash in C++.'
type: docs
weight: 400
url: /cpp/system.security.cryptography/dsasignaturedeformatter/verifysignature/
---
## DSASignatureDeformatter::VerifySignature method


Verifies the [DSA](../../dsa/) signature of the specified hash.

```cpp
bool System::Security::Cryptography::DSASignatureDeformatter::VerifySignature(ArrayPtr<uint8_t> rgbHash, ArrayPtr<uint8_t> rgbSignature) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | ArrayPtr\<uint8_t\> | Hash of the signed data. |
| rgbSignature | ArrayPtr\<uint8_t\> | Signature to verify. |

### ReturnValue

True if the signature is valid, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DSASignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
