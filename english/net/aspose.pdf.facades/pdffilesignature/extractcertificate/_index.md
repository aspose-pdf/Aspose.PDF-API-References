---
title: "PdfFileSignature.ExtractCertificate"
linktitle: "ExtractCertificate"
articleTitle: "ExtractCertificate"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSignature method. Extracts signature's single X.509 certificate as a stream."
type: docs
weight: 620
url: "/net/aspose.pdf.facades/pdffilesignature/extractcertificate/"
product_version: "26.9.0"
---
## ExtractCertificate(string) {#extractcertificate}

> **Deprecated.** Use ExtractCertificate(SignatureName) method instead.

Extracts signature's single X.509 certificate as a stream.

```csharp
public Stream ExtractCertificate(string signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | string | The name of signature. |

### Return Value

[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

If certificate was found returns X.509 single certificate; otherwise, null.

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractCertificate([SignatureName](../../../aspose.pdf.facades/signaturename/)) {#extractcertificate_1}

Extracts signature's single X.509 certificate as a stream.

```csharp
public Stream ExtractCertificate(SignatureName signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | The name of signature. |

### Return Value

[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

If a certificate was found returns X.509 single certificate; otherwise, null.

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

