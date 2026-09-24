---
title: "PdfFileSignature.VerifySignature"
linktitle: "VerifySignature"
articleTitle: "VerifySignature"
second_title: "Aspose.PDF for .NET"
description: "Checks the validity of a signature."
type: docs
weight: 490
url: "/net/aspose.pdf.facades/pdffilesignature/verifysignature/"
product_version: "26.9.0"
---
## VerifySignature(string) {#verifysignature}

> **Deprecated.** Use VerifySignature(SignatureName) method instead.

Checks the validity of a signature.

```csharp
public bool VerifySignature(string signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | string | The name of signature. |

### Return Value

bool

Return a result of bool type.

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature([SignatureName](../../../aspose.pdf.facades/signaturename/)) {#verifysignature_1}

Checks the validity of a signature.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |

### Return Value

bool

Return a result of bool type.

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(string, [ValidationOptions](../../../aspose.pdf.security/validationoptions/), [ValidationResult](../../../aspose.pdf.security/validationresult/)) {#verifysignature_2}

> **Deprecated.** Use VerifySignature(SignatureName, ValidationOptions, out ValidationResult) method instead.



```csharp
public bool VerifySignature(string signName, ValidationOptions options, ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | string |  |
| options | ValidationOptions |  |
| validationResult | ValidationResult |  |

### Return Value

bool

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature([SignatureName](../../../aspose.pdf.facades/signaturename/), [ValidationOptions](../../../aspose.pdf.security/validationoptions/), [ValidationResult](../../../aspose.pdf.security/validationresult/)) {#verifysignature_3}



```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName |  |
| options | ValidationOptions |  |
| validationResult | ValidationResult |  |

### Return Value

bool

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature([SignatureName](../../../aspose.pdf.facades/signaturename/), X509Certificate2, [ValidationOptions](../../../aspose.pdf.security/validationoptions/), [ValidationResult](../../../aspose.pdf.security/validationresult/)) {#verifysignature_4}



```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, ValidationOptions options, ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName |  |
| publicKeyCertificate | X509Certificate2 |  |
| options | ValidationOptions |  |
| validationResult | ValidationResult |  |

### Return Value

bool

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature([SignatureName](../../../aspose.pdf.facades/signaturename/), X509Certificate2) {#verifysignature_5}

Checks the validity of a signature.
 Verification is performed using the external public key certificate.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |

### Return Value

bool

Return a result of bool type.

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

