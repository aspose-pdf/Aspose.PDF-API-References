---
title: Signature.TryVerify
second_title: Aspose.PDF for .NET API Reference
description: Signature method. Try to verify the document regarding this signature and return true if document is valid or otherwise false
type: docs
weight: 170
url: /net/aspose.pdf.forms/signature/tryverify/
---
## TryVerify(out VerificationResult) {#tryverify_1}

Try to verify the document regarding this signature and return true if document is valid or otherwise false.

```csharp
public bool TryVerify(out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| verificationResult | VerificationResult& | The verification result. |

### Return Value

Returns true if the signature was processed correctly. Returns false if an error occurred during the verification process or the signature was corrupted or compromised.

### See Also

* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## TryVerify(ValidationOptions, out ValidationResult, out VerificationResult) {#tryverify}

Try to verify the document regarding this signature and return true if document is valid or otherwise false.

```csharp
public bool TryVerify(ValidationOptions options, out ValidationResult validationResult, 
    out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |
| verificationResult | VerificationResult& | The verification result. |

### Return Value

Returns true if the signature was processed correctly. Returns false if an error occurred during the verification process or the signature was corrupted or compromised.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## TryVerify(X509Certificate2, ValidationOptions, out ValidationResult, out VerificationResult) {#tryverify_2}

Try to verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate.

```csharp
public bool TryVerify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult, out VerificationResult verificationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |
| verificationResult | VerificationResult& | The verification result. |

### Return Value

Returns true if the signature was processed correctly. Returns false if an error occurred during the verification process or the signature was corrupted or compromised.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


