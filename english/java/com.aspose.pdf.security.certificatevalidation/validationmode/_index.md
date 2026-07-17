---
title: ValidationMode
linktitle: ValidationMode
second_title: Aspose.PDF for Java API Reference
description: Specifies the validation mode for PDF signature validation processes.
type: docs
weight: 20
url: /java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Specifies the validation mode for PDF signature validation processes.

## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Represents a mode where validation is not performed. |
| [OnlyCheck](#OnlyCheck) | Represents the mode in which the validation is made, but its result does not affect the validation of the digital signature. You can check the result of the validation yourself. |
| [Strict](#Strict) | Represents the mode in which the validation is made and its result affects the validation of the digital signature. If the certificate could not be verified, then the digital signature will be considered invalid. You can check the result of the validation yourself. |

### None {#None}
```
public static final int None
```

Represents a mode where validation is not performed.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Represents the mode in which the validation is made, but its result does not affect the validation of the digital signature. You can check the result of the validation yourself.

### Strict {#Strict}
```
public static final int Strict
```

Represents the mode in which the validation is made and its result affects the validation of the digital signature. If the certificate could not be verified, then the digital signature will be considered invalid. You can check the result of the validation yourself.
