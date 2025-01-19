---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature method. Checks the validity of a signature
type: docs
weight: 310
url: /net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(string) {#verifysignature}

Checks the validity of a signature.

```csharp
public bool VerifySignature(string signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | String | The name of signature. |

### Return Value

Return a result of bool type.

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(string, ValidationOptions, out ValidationResult) {#verifysignature_1}

Checks the validity of a signature.

```csharp
public bool VerifySignature(string signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | String | The name of signature. |
| options | ValidationOptions | The verification options. |
| validationResult | ValidationResult& | The certificate validation result. |

### Return Value

Return a result of bool type.

## Remarks

This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


