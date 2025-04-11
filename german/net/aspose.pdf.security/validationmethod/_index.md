---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod-Enum. Stellt ein Enum dar, das die Methode für die Zertifikatsvalidierung definiert
type: docs
weight: 10050
url: /de/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod-Enumeration

Stellt ein Enum dar, das die Methode für die Zertifikatsvalidierung definiert.

```csharp
public enum ValidationMethod
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Bestimmt automatisch die beste Methode zur Zertifikatsvalidierung. |
| Ocsp | `1` | Verwendet das Online Certificate Status Protocol (OCSP) zur Zertifikatsvalidierung. OCSP ist ein Protokoll, das den Validierungsstatus eines Zertifikats durch direkte Abfrage der ausstellenden Zertifizierungsstelle (CA) bereitstellt. |
| Crl | `2` | Validiert Zertifikate mithilfe der Methode der Zertifikatswiderrufsliste (CRL). |
| Alle | `3` | Verwendet alle verfügbaren Methoden (OCSP und CRL) zur Zertifikatsvalidierung. |

### Siehe auch

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)