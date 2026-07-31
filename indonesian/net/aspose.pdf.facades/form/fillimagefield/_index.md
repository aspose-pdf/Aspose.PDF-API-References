---
title: "Form.FillImageField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Menempelkan gambar ke bidang tombol yang ada sebagai tampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat"
type: docs
weight: 150
url: /id/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Menempelkan gambar ke bidang tombol yang ada sebagai tampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang lengkap dari bidang tombol gambar. |
| imageFileName | String | Jalur file gambar, relatif dan absolut keduanya ok. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Membebani fungsi FillImageField. Inputnya adalah aliran gambar.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi kualifikasi. |
| imageStream | Stream | Stream gambar. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


