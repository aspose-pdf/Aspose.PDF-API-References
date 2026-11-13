---
title: Aspose::Pdf::Security::SignatureAlgorithmInfo class
linktitle: SignatureAlgorithmInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::SignatureAlgorithmInfo class. Represents a class for information about a signature algorithm, including its type, cryptographic standard, and digest hash algorithm in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo class


Represents a class for information about a signature algorithm, including its type, cryptographic standard, and digest hash algorithm.

```cpp
class SignatureAlgorithmInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_SignatureName](./get_signaturename/)() const | Gets the name of the signature field. |
| [ToString](./tostring/)() const override | Converts the current information object to its string representation. |
## Fields

| Field | Description |
| --- | --- |
| [AlgorithmType](./algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. |
| [CryptographicStandard](./cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. For a timestamp, this is the digest hash algorithm with which the hash of the document content is signed. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
