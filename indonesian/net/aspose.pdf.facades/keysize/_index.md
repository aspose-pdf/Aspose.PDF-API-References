---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Enum KeySize Aspose.Pdf.Facades. Mendefinisikan berbagai ukuran kunci yang dapat digunakan untuk mengenkripsi dokumen pdf
type: docs
weight: 4390
url: /id/net/aspose.pdf.facades/keysize/
---
## Enumerasi KeySize

Mendefinisikan berbagai ukuran kunci yang dapat digunakan untuk mengenkripsi dokumen pdf.

```csharp
public enum KeySize
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| x40 | `0` | Kunci 40 bit. Ukuran kunci seperti ini digunakan dengan algoritma RC4 dan memberikan tingkat keamanan yang rendah. Namun, versi lama dokumen pdf hanya dapat dienkripsi dengan kunci seperti ini (v. 1.3 dan lebih rendah); |
| x128 | `1` | Kunci 128 bit. Baik algoritma RC4 maupun AES dapat menggunakan ukuran kunci seperti ini. |
| x256 | `2` | Kunci 256 bit. Ukuran kunci seperti ini hanya dapat digunakan dengan AES dan dikenali dengan versi Adobe Reader terbaru (mulai dari v.9). |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)