---
title: Aspose::Pdf::Security::KeyedSignatureAlgorithmInfo class
linktitle: KeyedSignatureAlgorithmInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::KeyedSignatureAlgorithmInfo class. Represents a class for information about a keyed signature algorithm in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.security/keyedsignaturealgorithminfo/
---
## KeyedSignatureAlgorithmInfo class


Represents a class for information about a keyed signature algorithm.

```cpp
class KeyedSignatureAlgorithmInfo : public Aspose::Pdf::Security::SignatureAlgorithmInfo
```

## Fields

| Field | Description |
| --- | --- |
| [AlgorithmType](../signaturealgorithminfo/algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. |
| [CryptographicStandard](../signaturealgorithminfo/cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| [DigestHashAlgorithm](../signaturealgorithminfo/digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. For a timestamp, this is the digest hash algorithm with which the hash of the document content is signed. |
| [KeySize](./keysize/) | Gets the size of the cryptographic key used by the signature algorithm. |
## See Also

* Class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
