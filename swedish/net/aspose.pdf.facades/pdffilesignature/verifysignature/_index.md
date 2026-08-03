---
title: "PdfFileSignature.VerifySignature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSignature-metoden. Kontrollerar giltigheten för en signatur"
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Kontrollerar giltigheten för en signatur.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |

### Returvärde

Returnerar ett resultat av bool‑typ.

### Se även

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Kontrollerar giltigheten för en signatur.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| options | ValidationOptions | Verifieringsalternativen. |
| validationResult | ValidationResult& | Certifikatvalideringsresultatet. |

### Returvärde

Returnerar ett resultat av bool‑typ.

## Anmärkningar

Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certificate revocation list) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.

### Se även

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| publicKeyCertificate | X509Certificate2 | Det offentliga nyckelcertifikatet för verifiering. |
| options | ValidationOptions | Verifieringsalternativen. |
| validationResult | ValidationResult& | Certifikatvalideringsresultatet. |

### Returvärde

Returnerar ett resultat av bool‑typ.

## Anmärkningar

Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certificate revocation list) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.

### Se även

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| publicKeyCertificate | X509Certificate2 | Det offentliga nyckelcertifikatet för verifiering. |

### Returvärde

Returnerar ett resultat av bool‑typ.

### Se även

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


