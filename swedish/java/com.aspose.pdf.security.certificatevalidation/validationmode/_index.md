---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger valideringsläget för PDF‑signaturvalideringsprocesser."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Anger valideringsläget för PDF‑signaturvalideringsprocesser.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [None](#None) | Representerar ett läge där validering inte utförs. |
| [OnlyCheck](#OnlyCheck) | Representerar det läge i vilket valideringen utförs, men dess resultat påverkar inte valideringen av den digitala signaturen. Du kan kontrollera valideringsresultatet själv. |
| [Strict](#Strict) | Representerar det läge i vilket valideringen utförs och dess resultat påverkar valideringen av den digitala signaturen. Om certifikatet inte kunde verifieras kommer den digitala signaturen att betraktas som ogiltig. Du kan kontrollera valideringsresultatet själv. |

### None {#None}
```
public static final int None
```

Representerar ett läge där validering inte utförs.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Representerar det läge i vilket valideringen utförs, men dess resultat påverkar inte valideringen av den digitala signaturen. Du kan kontrollera valideringsresultatet själv.

### Strict {#Strict}
```
public static final int Strict
```

Representerar det läge i vilket valideringen utförs och dess resultat påverkar valideringen av den digitala signaturen. Om certifikatet inte kunde verifieras kommer den digitala signaturen att betraktas som ogiltig. Du kan kontrollera valideringsresultatet själv.
