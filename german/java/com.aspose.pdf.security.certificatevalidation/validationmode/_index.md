---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt den Validierungsmodus für PDF‑Signaturvalidierungsprozesse an."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Gibt den Validierungsmodus für PDF‑Signaturvalidierungsprozesse an.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Stellt einen Modus dar, bei dem keine Validierung durchgeführt wird. |
| [OnlyCheck](#OnlyCheck) | Stellt den Modus dar, in dem die Validierung durchgeführt wird, deren Ergebnis jedoch die Validierung der digitalen Signatur nicht beeinflusst. Sie können das Ergebnis der Validierung selbst überprüfen. |
| [Strict](#Strict) | Stellt den Modus dar, in dem die Validierung durchgeführt wird und ihr Ergebnis die Validierung der digitalen Signatur beeinflusst. Wenn das Zertifikat nicht verifiziert werden konnte, wird die digitale Signatur als ungültig betrachtet. Sie können das Ergebnis der Validierung selbst überprüfen. |

### None {#None}
```
public static final int None
```

Stellt einen Modus dar, bei dem keine Validierung durchgeführt wird.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Stellt den Modus dar, in dem die Validierung durchgeführt wird, deren Ergebnis jedoch die Validierung der digitalen Signatur nicht beeinflusst. Sie können das Ergebnis der Validierung selbst überprüfen.

### Strict {#Strict}
```
public static final int Strict
```

Stellt den Modus dar, in dem die Validierung durchgeführt wird und ihr Ergebnis die Validierung der digitalen Signatur beeinflusst. Wenn das Zertifikat nicht verifiziert werden konnte, wird die digitale Signatur als ungültig betrachtet. Sie können das Ergebnis der Validierung selbst überprüfen.
