---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode-Enum. Gibt den Validierungsmodus für PDF-Signaturvalidierungsprozesse an
type: docs
weight: 10060
url: /de/net/aspose.pdf.security/validationmode/
---
## ValidationMode-Enumeration

Gibt den Validierungsmodus für PDF-Signaturvalidierungsprozesse an.

```csharp
public enum ValidationMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Stellt einen Modus dar, in dem keine Validierung durchgeführt wird. |
| OnlyCheck | `1` | Stellt den Modus dar, in dem die Validierung durchgeführt wird, aber das Ergebnis keinen Einfluss auf die Validierung der digitalen Signatur hat. Sie können das Ergebnis der Validierung selbst überprüfen. |
| Strict | `2` | Stellt den Modus dar, in dem die Validierung durchgeführt wird und das Ergebnis die Validierung der digitalen Signatur beeinflusst. Wenn das Zertifikat nicht verifiziert werden konnte, wird die digitale Signatur als ungültig betrachtet. Sie können das Ergebnis der Validierung selbst überprüfen. |

### Siehe auch

* Namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* Assembly [Aspose.PDF](../../)