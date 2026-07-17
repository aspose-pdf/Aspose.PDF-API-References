---
title: Aspose::Pdf::Security::VerificationResult class
linktitle: VerificationResult
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::VerificationResult class. Represents the result of verifying a digital signature in a PDF file in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.security/verificationresult/
---
## VerificationResult class


Represents the result of verifying a digital signature in a PDF file.

```cpp
class VerificationResult : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsCompromised](./get_iscompromised/)() const | Indicates whether the digital signature structure is likely compromised. This means a change to bypass signature checking by PDF tools. See [Message](../) for more details. |
| [get_Message](./get_message/)() const | Gets the message associated with the verification result. The property value provides additional details about the verification outcome, such as error descriptions or success messages. |
| [get_State](./get_state/)() const | Represents the verification state of a digital signature in a PDF file. Indicates whether the signature is valid, invalid, or undefined. |
| [get_VerificationException](./get_verificationexception/)() const | Gets the exception associated with the verification process if presents. This property provides details about errors or issues encountered during the verification of a digital signature in a PDF file. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
