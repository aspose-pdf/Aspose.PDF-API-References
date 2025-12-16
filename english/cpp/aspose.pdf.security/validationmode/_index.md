---
title: Aspose::Pdf::Security::ValidationMode enum
linktitle: ValidationMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ValidationMode enum. Specifies the validation mode for PDF signature validation processes in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.security/validationmode/
---
## ValidationMode enum


Specifies the validation mode for PDF signature validation processes.

```cpp
enum class ValidationMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Represents a mode where validation is not performed. |
| OnlyCheck | 1 | Represents the mode in which the validation is made, but its result does not affect the validation of the digital signature. You can check the result of the validation yourself. |
| Strict | 2 | Represents the mode in which the validation is made and its result affects the validation of the digital signature. If the certificate could not be verified, then the digital signature will be considered invalid. You can check the result of the validation yourself. |

## See Also

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
