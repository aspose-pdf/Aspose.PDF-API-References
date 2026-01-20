---
title: System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature method. Verifies the signature of data hash in C++.'
type: docs
weight: 400
url: /cpp/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature method


Verifies the signature of data hash.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | Hash calculated for the data. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signature received for data. |

### ReturnValue

True if signature is valid, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
