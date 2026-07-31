---
title: "PdfFileSignature.Certify"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileSignature. Menyertifikasi dokumen dengan tanda tangan MDP. Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Signature sig"
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Sertakan dokumen dengan tanda tangan MDP. Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan melalui properti yang sesuai dari objek Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Int32 | Halaman tempat tanda tangan dibuat. |
| SigReason | String | Alasan tanda tangan. |
| SigContact | String | Kontak tanda tangan. |
| SigLocation | String | Lokasi tanda tangan. |
| terlihat | Boolean | Visibilitas tanda tangan. |
| annotRect | Rectangle | Kotak tanda tangan. |
| docMdpSignature | DocMDPSignature | Tipe MDP dokumen dari tanda tangan. |

### Lihat Juga

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Sertakan dokumen dengan tanda tangan MDP yang ditempatkan pada bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Karena dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan; halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sigName | String | Nama bidang tanda tangan. |
| docMdpSignature | DocMDPSignature | Tipe tanda tangan, dapat berupa [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) dan [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Lihat Juga

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


