---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica el modo de validación para los procesos de validación de firmas PDF."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Especifica el modo de validación para los procesos de validación de firmas PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | Representa un modo en el que no se realiza la validación. |
| [OnlyCheck](#OnlyCheck) | Representa el modo en el que se realiza la validación, pero su resultado no afecta la validación de la firma digital. Puedes comprobar el resultado de la validación tú mismo. |
| [Strict](#Strict) | Representa el modo en el que se realiza la validación y su resultado afecta la validación de la firma digital. Si el certificado no pudo ser verificado, entonces la firma digital se considerará inválida. Puedes comprobar el resultado de la validación tú mismo. |

### None {#None}
```
public static final int None
```

Representa un modo en el que no se realiza la validación.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Representa el modo en el que se realiza la validación, pero su resultado no afecta la validación de la firma digital. Puedes comprobar el resultado de la validación tú mismo.

### Strict {#Strict}
```
public static final int Strict
```

Representa el modo en el que se realiza la validación y su resultado afecta la validación de la firma digital. Si el certificado no pudo ser verificado, entonces la firma digital se considerará inválida. Puedes comprobar el resultado de la validación tú mismo.
