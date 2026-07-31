---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileSignature. Mengekstrak sertifikat X.509 tunggal tanda tangan"
type: docs
weight: 310
url: /id/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Mengekstrak sertifikat X.509 tunggal dari tanda tangan.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| sertifikat | X509Certificate2& | Jika sertifikat ditemukan mengembalikan objek sertifikat X.509 tunggal; jika tidak, null. |

### Nilai Kembalian

Sertifikat ditemukan.

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| stream | Stream& | Jika sertifikat ditemukan mengembalikan stream sertifikat X.509 tunggal; jika tidak, null. |

### Nilai Kembalian

Sertifikat ditemukan.

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


