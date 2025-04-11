---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSignature. Mensertifikasi dokumen dengan tanda tangan MDP. Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Signature sig
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Mensertifikasi dokumen dengan tanda tangan MDP. Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Halaman di mana tanda tangan dibuat. |
| SigReason | String | Alasan tanda tangan. |
| SigContact | String | Kontak tanda tangan. |
| SigLocation | String | Lokasi tanda tangan. |
| visible | Boolean | Visibilitas tanda tangan. |
| annotRect | Rectangle | Rect tanda tangan. |
| docMdpSignature | DocMDPSignature | Jenis tanda tangan MDP dokumen. |

### Lihat Juga

* kelas [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* kelas [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Mensertifikasi dokumen dengan tanda tangan MDP yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh mengandung kamus tanda tangan. Dengan demikian, dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sigName | String | Nama bidang tanda tangan. |
| docMdpSignature | DocMDPSignature | Jenis tanda tangan, bisa berupa [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) dan [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Lihat Juga

* kelas [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* kelas [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)