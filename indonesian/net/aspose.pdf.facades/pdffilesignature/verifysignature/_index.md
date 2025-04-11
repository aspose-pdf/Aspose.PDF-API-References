---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSignature. Memeriksa keabsahan tanda tangan
type: docs
weight: 310
url: /id/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Memeriksa keabsahan tanda tangan.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |

### Return Value

Mengembalikan hasil tipe bool.

### See Also

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Memeriksa keabsahan tanda tangan.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| options | ValidationOptions | Opsi verifikasi. |
| validationResult | ValidationResult& | Hasil validasi sertifikat. |

### Return Value

Mengembalikan hasil tipe bool.

## Remarks

Metode ini memungkinkan Anda untuk memeriksa sertifikat tanda tangan menggunakan OCSP dan/atau CRL (daftar pencabutan sertifikat) untuk pencabutan. Metode ini tidak memeriksa rantai sertifikat dan keabsahannya, tetapi memeriksa apakah sertifikat akhir telah dicabut.

### See Also

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)