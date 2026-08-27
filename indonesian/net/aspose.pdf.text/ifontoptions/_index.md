---
title: "Antarmuka IFontOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Antarmuka Aspose.Pdf.Text.IFontOptions. Properti berguna untuk menyesuaikan perilaku Font."
type: docs
weight: 10790
url: /id/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Properti berguna untuk menyesuaikan perilaku Font

```csharp
public interface IFontOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Terkadang tidak memungkinkan untuk menyematkan font yang diinginkan ke dalam dokumen. Ada banyak alasan, misalnya pembatasan lisensi atau ketika font yang diinginkan tidak ditemukan di komputer tujuan. Ketika situasi ini muncul, tidak mudah dideteksi, karena font yang diinginkan disematkan melalui properti flag `Font.IsEmbedded = true;`. Tentu saja properti ini dapat dibaca segera setelah diatur, tetapi pendekatan ini tidak nyaman. Flag NotifyAboutFontEmbeddingError memaksa mekanisme pengecualian untuk kasus ketika upaya menyematkan font gagal. Jika flag ini diatur, pengecualian bertipe [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) akan dilempar. Secara default false. |

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


