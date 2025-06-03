---
title: PdfFileSignature.TryExtractCertificate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature method. Extracts signatures single X.509 certificate
type: docs
weight: 310
url: /net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Extracts signature's single X.509 certificate.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| certificate | X509Certificate2& | If a certificate was found returns X.509 single certificate object; otherwise, null. |

### Return Value

True certificate was found.

### See Also

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Extracts signature's single X.509 certificate as a stream.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |
| stream | Stream& | If a certificate was found returns X.509 single certificate stream; otherwise, null. |

### Return Value

True certificate was found.

### See Also

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


