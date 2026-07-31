---
title: "PdfFileSignature.VerifySignature"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileSignature. Memeriksa keabsahan sebuah tanda tangan."
type: docs
weight: 320
url: /id/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Memeriksa keabsahan sebuah tanda tangan.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |

### Nilai Kembalian

Kembalikan hasil dengan tipe bool.

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Memeriksa keabsahan sebuah tanda tangan.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| options | ValidationOptions | Opsi verifikasi. |
| validationResult | ValidationResult& | Hasil validasi sertifikat. |

### Nilai Kembalian

Kembalikan hasil dengan tipe bool.

## Catatan

Metode ini memungkinkan Anda memeriksa sertifikat penandatangan menggunakan OCSP dan/atau CRL (daftar pencabutan sertifikat) untuk pencabutan. Metode ini tidak memeriksa rantai sertifikat dan keabsahannya, tetapi memeriksa apakah sertifikat akhir telah dicabut.

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

Memeriksa keabsahan sebuah tanda tangan. Verifikasi dilakukan menggunakan sertifikat kunci publik eksternal.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| publicKeyCertificate | X509Certificate2 | Sertifikat kunci publik untuk verifikasi. |
| options | ValidationOptions | Opsi verifikasi. |
| validationResult | ValidationResult& | Hasil validasi sertifikat. |

### Nilai Kembalian

Kembalikan hasil dengan tipe bool.

## Catatan

Metode ini memungkinkan Anda memeriksa sertifikat penandatangan menggunakan OCSP dan/atau CRL (daftar pencabutan sertifikat) untuk pencabutan. Metode ini tidak memeriksa rantai sertifikat dan keabsahannya, tetapi memeriksa apakah sertifikat akhir telah dicabut.

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

Memeriksa keabsahan sebuah tanda tangan. Verifikasi dilakukan menggunakan sertifikat kunci publik eksternal.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| publicKeyCertificate | X509Certificate2 | Sertifikat kunci publik untuk verifikasi. |

### Nilai Kembalian

Kembalikan hasil dengan tipe bool.

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


