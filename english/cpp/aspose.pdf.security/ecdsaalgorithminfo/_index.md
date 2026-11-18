---
title: Aspose::Pdf::Security::EcdsaAlgorithmInfo class
linktitle: EcdsaAlgorithmInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::EcdsaAlgorithmInfo class. Represents a class for the information about the ECDSA signature algorithm in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo class


Represents a class for the information about the ECDSA signature algorithm.

```cpp
class EcdsaAlgorithmInfo : public Aspose::Pdf::Security::KeyedSignatureAlgorithmInfo
```

## Fields

| Field | Description |
| --- | --- |
| [AlgorithmType](../signaturealgorithminfo/algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. |
| [CryptographicStandard](../signaturealgorithminfo/cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| [DigestHashAlgorithm](../signaturealgorithminfo/digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. For a timestamp, this is the digest hash algorithm with which the hash of the document content is signed. |
| [EccName](./eccname/) | Gets the name of the elliptic curve used by the ECDSA. |
| [KeySize](../keyedsignaturealgorithminfo/keysize/) | Gets the size of the cryptographic key used by the signature algorithm. |
## See Also

* Class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
