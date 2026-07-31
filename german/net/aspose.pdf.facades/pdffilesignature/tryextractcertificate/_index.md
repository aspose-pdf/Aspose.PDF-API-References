---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "PdfFileSignature-Methode. Extrahiert das einzelne X.509-Zertifikat einer Signatur"
type: docs
weight: 310
url: /de/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Extrahiert das einzelne X.509-Zertifikat der Signatur.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | SignatureName | Der Name der Signatur. |
| certificate | X509Certificate2& | Wenn ein Zertifikat gefunden wurde, wird das einzelne X.509-Zertifikatsobjekt zurückgegeben; andernfalls null. |

### Rückgabewert

Ein gültiges Zertifikat wurde gefunden.

### Siehe auch

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | SignatureName | Der Name der Signatur. |
| Strom | Stream& | Wenn ein Zertifikat gefunden wurde, gibt es den X.509 Einzelzertifikat‑Stream zurück; andernfalls null. |

### Rückgabewert

Ein gültiges Zertifikat wurde gefunden.

### Siehe auch

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


