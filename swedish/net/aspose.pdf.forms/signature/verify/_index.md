---
title: "Signature.Verify"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Signature‑metod. Verifiera dokumentet med avseende på denna signatur och returnera sant om dokumentet är giltigt, annars falskt"
type: docs
weight: 170
url: /sv/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

```csharp
public bool Verify()
```

### Returvärde

Sant om dokumentet är giltigt.

### Se även

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ValidationOptions | Verifieringsalternativen. |
| validationResult | ValidationResult& | Certifikatvalideringsresultatet. |

### Returvärde

Sant om dokumentet är giltigt.

### Se även

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | Det offentliga nyckelcertifikatet för verifiering. |
| options | ValidationOptions | Verifieringsalternativen. |
| validationResult | ValidationResult& | Certifikatvalideringsresultatet. |

### Returvärde

Sant om dokumentet är giltigt.

### Se även

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


