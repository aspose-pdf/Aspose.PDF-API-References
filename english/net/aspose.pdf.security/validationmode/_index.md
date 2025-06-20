---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode enum. Specifies the validation mode for PDF signature validation processes
type: docs
weight: 10210
url: /net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

Specifies the validation mode for PDF signature validation processes.

```csharp
public enum ValidationMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | Represents a mode where validation is not performed. |
| OnlyCheck | `1` | Represents the mode in which the validation is made, but its result does not affect the validation of the digital signature. You can check the result of the validation yourself. |
| Strict | `2` | Represents the mode in which the validation is made and its result affects the validation of the digital signature. If the certificate could not be verified, then the digital signature will be considered invalid. You can check the result of the validation yourself. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


