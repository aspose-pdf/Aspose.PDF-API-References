---
title: "Enum KeySize"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Facades.KeySize. Menentukan berbagai ukuran kunci yang dapat digunakan untuk mengenkripsi dokumen pdf"
type: docs
weight: 4510
url: /id/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

Mendefinisikan ukuran kunci yang berbeda yang dapat digunakan untuk mengenkripsi pdf documents.

```csharp
public enum KeySize
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| x40 | `0` | Kunci 40 bit. Ukuran kunci tersebut digunakan dengan algoritma RC4 dan memberikan tingkat keamanan yang rendah. Namun versi lama dokumen pdf hanya dapat dienkripsi dengan kunci tersebut (v. 1.3 dan lebih rendah); |
| x128 | `1` | Kunci 128 bit. Baik algoritma RC4 maupun AES dapat menggunakan ukuran kunci tersebut. |
| x256 | `2` | Kunci 256 bit. Ukuran kunci tersebut hanya dapat digunakan dengan AES dan dikenali pada versi Adobe Reader terbaru (mulai v.9). |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


