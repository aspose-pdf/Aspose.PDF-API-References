---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica o modo de validação para processos de validação de assinatura PDF."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Especifica o modo de validação para processos de validação de assinatura PDF.

## Campos

| Campo | Descrição |
| --- | --- |
| [None](#None) | Representa um modo onde a validação não é realizada. |
| [OnlyCheck](#OnlyCheck) | Representa o modo em que a validação é feita, mas seu resultado não afeta a validação da assinatura digital. Você pode verificar o resultado da validação por conta própria. |
| [Strict](#Strict) | Representa o modo em que a validação é feita e seu resultado afeta a validação da assinatura digital. Se o certificado não puder ser verificado, a assinatura digital será considerada inválida. Você pode verificar o resultado da validação por conta própria. |

### None {#None}
```
public static final int None
```

Representa um modo onde a validação não é realizada.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Representa o modo em que a validação é feita, mas seu resultado não afeta a validação da assinatura digital. Você pode verificar o resultado da validação por conta própria.

### Strict {#Strict}
```
public static final int Strict
```

Representa o modo em que a validação é feita e seu resultado afeta a validação da assinatura digital. Se o certificado não puder ser verificado, a assinatura digital será considerada inválida. Você pode verificar o resultado da validação por conta própria.
