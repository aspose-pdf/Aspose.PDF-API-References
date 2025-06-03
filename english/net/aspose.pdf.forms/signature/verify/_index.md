---
title: Signature.Verify
second_title: Aspose.PDF for .NET API Reference
description: Signature method. Verify the document regarding this signature and return true if document is valid or otherwise false
type: docs
weight: 170
url: /net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Verify the document regarding this signature and return true if document is valid or otherwise false.

```csharp
public bool Verify()
```

### Return Value

true if document is valid.

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Verify the document regarding this signature and return true if document is valid or otherwise false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value

true if document is valid.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | The public key certificate for verification. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value

true if document is valid.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


