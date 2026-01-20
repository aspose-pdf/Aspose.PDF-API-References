---
title: Aspose::Pdf::Signatures::SignaturesCoverage enum
linktitle: SignaturesCoverage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Signatures::SignaturesCoverage enum. Represents enum for the level of coverage provided by digital signatures in a document in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enum


Represents enum for the level of coverage provided by digital signatures in a document.

```cpp
enum class SignaturesCoverage
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Undefined | 0 | Indicates that the state of digital signatures' coverage in the document is undefined. This value is typically used when one or more signatures in the document are compromised or cannot be verified, preventing a definitive assessment of the document's signature coverage. |
| EntirelySigned | 1 | Indicates that the document is entirely covered by digital signatures. This value signifies that all required portions of the document have been signed and no signatures are compromised. |
| PartiallySigned | 2 | Indicates that the document is partially signed, meaning that some, but not all, of its content is covered by digital signatures. This value is used when certain parts of the document remain unsigned or are excluded from the signature coverage. |

## See Also

* Namespace [Aspose::Pdf::Signatures](../)
* Library [Aspose.PDF for C++](../../)
