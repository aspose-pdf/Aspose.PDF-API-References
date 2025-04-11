---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature metodu. Bir imzanın geçerliliğini kontrol eder
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Bir imzanın geçerliliğini kontrol eder.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signName | SignatureName | İmzanın adı. |

### Dönüş Değeri

bool türünde bir sonuç döner.

### Ayrıca Bakınız

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Bir imzanın geçerliliğini kontrol eder.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signName | SignatureName | İmzanın adı. |
| options | ValidationOptions | Doğrulama seçenekleri. |
| validationResult | ValidationResult& | Sertifika doğrulama sonucu. |

### Dönüş Değeri

bool türünde bir sonuç döner.

## Açıklamalar

Bu yöntem, iptal için OCSP ve/veya CRL (sertifika iptal listesi) kullanarak imzalama sertifikasını kontrol etmenizi sağlar. Bu yöntem, sertifika zincirini ve geçerliliğini kontrol etmez, ancak son sertifikanın iptal edilip edilmediğini kontrol eder.

### Ayrıca Bakınız

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)