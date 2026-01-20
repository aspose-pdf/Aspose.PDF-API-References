---
title: Aspose::Pdf::DigestHashAlgorithm enum
linktitle: DigestHashAlgorithm
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DigestHashAlgorithm enum. Represent type of algorithm that maps data to a "hash" in C++.'
type: docs
weight: 22800
url: /cpp/aspose.pdf/digesthashalgorithm/
---
## DigestHashAlgorithm enum


Represent type of algorithm that maps data to a "hash".

```cpp
enum class DigestHashAlgorithm
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Automatic setting of the hashing algorithm at the discretion of the signature algorithm. For EDCSA, the default value is determined by the key size. The default value for a not detached PKCS7 is Sha1. |
| Sha1 | 1 | SHA-1. Secure Hash Algorithm 1 It is a default value for a not detached PKCS7. |
| Sha256 | 2 | SHA-256. Secure Hash Algorithm 2 It is a default value for a detached PKCS7. |
| Sha384 | 3 | SHA-384. Secure Hash Algorithm 2. |
| Sha512 | 4 | SHA-512. Secure Hash Algorithm 2. |
| Sha3_256 | 5 | SHA3-256. Secure Hash Algorithm 3. |
| Sha3_384 | 6 | SHA3-384. Secure Hash Algorithm 3. |
| Sha3_512 | 7 | SHA3-512. Secure Hash Algorithm 3. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
