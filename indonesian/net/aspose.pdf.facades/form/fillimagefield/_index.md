---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Menempelkan gambar pada bidang tombol yang ada sebagai tampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat
type: docs
weight: 150
url: /id/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Menempelkan gambar pada bidang tombol yang ada sebagai tampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang gambar tombol yang sepenuhnya memenuhi syarat. |
| imageFileName | String | Jalur file gambar, relatif dan absolut keduanya diperbolehkan. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Overload fungsi FillImageField. Inputnya adalah aliran gambar.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi syarat. |
| imageStream | Stream | Aliran gambar. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)