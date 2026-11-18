---
title: PdfFileSignature.TryVerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature method. Try to check the validity of a signature
type: docs
weight: 320
url: /net/aspose.pdf.facades/pdffilesignature/tryverifysignature/
---
## TryVerifySignature(SignatureName, out VerificationResult) {#tryverifysignature_1}

Try to check the validity of a signature.

```csharp
public bool TryVerifySignature(SignatureName signName, out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| verificationResult | VerificationResult& | The result of verification. |

### Return Value

Returns `true` if the signature was processed correctly. Returns `false` if an error occurred during the verification process or the signature was corrupted or compromised.

### See Also

* class [SignatureName](../../signaturename/)
* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryVerifySignature(SignatureName, ValidationOptions, out ValidationResult, out VerificationResult) {#tryverifysignature}

Try to check the validity of a signature.

```csharp
public bool TryVerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult, out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |
| verificationResult | VerificationResult& | The verification result. |

### Return Value

Returns `true` if the signature was processed correctly. Returns `false` if an error occurred during the verification process or the signature was corrupted or compromised.

## Remarks

This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked.

### See Also

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryVerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult, out VerificationResult) {#tryverifysignature_2}

Try to check the validity of a signature. Verification is performed using the external public key certificate.

```csharp
public bool TryVerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult, 
    out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |
| verificationResult | VerificationResult& | The result of verification. |

### Return Value

Returns `true` if the signature was processed correctly. Returns `false` if an error occurred during the verification process or the signature was corrupted or compromised.

## Remarks

This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked.

### See Also

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryVerifySignature(SignatureName, X509Certificate2, out VerificationResult) {#tryverifysignature_3}

Try to check the validity of a signature. Verification is performed using the external public key certificate.

```csharp
public bool TryVerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |
| verificationResult | VerificationResult& | The result of verification. |

### Return Value

Returns `true` if the signature was processed correctly. Returns `false` if an error occurred during the verification process or the signature was corrupted or compromised.

### See Also

* class [SignatureName](../../signaturename/)
* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


