---
title: Aspose::Pdf::Security::TimestampAlgorithmInfo class
linktitle: TimestampAlgorithmInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::TimestampAlgorithmInfo class. Represents a class for the information about the timestamp signature algorithm in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class


Represents a class for the information about the timestamp signature algorithm.

```cpp
class TimestampAlgorithmInfo : public Aspose::Pdf::Security::SignatureAlgorithmInfo
```

## Fields

| Field | Description |
| --- | --- |
| [AlgorithmType](../signaturealgorithminfo/algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. |
| [ContentHashAlgorithm](./contenthashalgorithm/) | Gets the hash algorithm that hashed the content of the document and then signed it using [SignatureAlgorithmInfo::DigestHashAlgorithm](../signaturealgorithminfo/digesthashalgorithm/). |
| [CryptographicStandard](../signaturealgorithminfo/cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| [DigestHashAlgorithm](../signaturealgorithminfo/digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. For a timestamp, this is the digest hash algorithm with which the hash of the document content is signed. |
## See Also

* Class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
