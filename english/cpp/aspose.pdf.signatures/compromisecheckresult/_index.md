---
title: Aspose::Pdf::Signatures::CompromiseCheckResult class
linktitle: CompromiseCheckResult
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Signatures::CompromiseCheckResult class. Represents a class for checking document digital signatures for compromise in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult class


Represents a class for checking document digital signatures for compromise.

```cpp
class CompromiseCheckResult : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_HasCompromisedSignatures](./get_hascompromisedsignatures/)() | Indicates whether there are any compromised digital signatures in the document. Returns true if at least one signature is compromised; otherwise, false. |
| [get_SignaturesCoverage](./get_signaturescoverage/)() const | Gets the coverage state of digital signatures in a document. If it is equal to [SignaturesCoverage::Undefined](../signaturescoverage/), then one of the signatures is compromised. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Signatures](../)
* Library [Aspose.PDF for C++](../../)
