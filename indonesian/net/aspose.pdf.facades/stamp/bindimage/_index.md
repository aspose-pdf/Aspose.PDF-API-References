---
title: "Stamp.BindImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Stamp. Menetapkan gambar sebagai stempel"
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
| imageFile | String | Nama file gambar dan jalurnya. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* class [Stamp](../)
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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


