---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica la modalità di convalida per i processi di convalida delle firme PDF."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Specifica la modalità di convalida per i processi di convalida delle firme PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Rappresenta una modalità in cui la convalida non viene eseguita. |
| [OnlyCheck](#OnlyCheck) | Rappresenta la modalità in cui viene eseguita la convalida, ma il suo risultato non influisce sulla convalida della firma digitale. È possibile verificare il risultato della convalida autonomamente. |
| [Strict](#Strict) | Rappresenta la modalità in cui viene eseguita la convalida e il suo risultato influisce sulla convalida della firma digitale. Se il certificato non può essere verificato, la firma digitale sarà considerata non valida. È possibile verificare il risultato della convalida autonomamente. |

### None {#None}
```
public static final int None
```

Rappresenta una modalità in cui la convalida non viene eseguita.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Rappresenta la modalità in cui viene eseguita la convalida, ma il suo risultato non influisce sulla convalida della firma digitale. È possibile verificare il risultato della convalida autonomamente.

### Strict {#Strict}
```
public static final int Strict
```

Rappresenta la modalità in cui viene eseguita la convalida e il suo risultato influisce sulla convalida della firma digitale. Se il certificato non può essere verificato, la firma digitale sarà considerata non valida. È possibile verificare il risultato della convalida autonomamente.
