---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Metode Stamp. Mengatur gambar sebagai stempel
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Mengatur gambar sebagai stempel.

```csharp
public void BindImage(string imageFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | String | Nama dan jalur file gambar. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Mengatur gambar yang akan digunakan sebagai stempel.

```csharp
public void BindImage(Stream image)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | Stream | Stream yang berisi data gambar. |

### Lihat Juga

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)