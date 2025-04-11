---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Antarmuka Aspose.Pdf.Text.IFontOptions. Properti berguna untuk mengatur perilaku Font
type: docs
weight: 10610
url: /id/net/aspose.pdf.text/ifontoptions/
---
## Antarmuka IFontOptions

Properti berguna untuk mengatur perilaku Font

```csharp
public interface IFontOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Terkadang tidak mungkin untuk menyematkan font yang diinginkan ke dalam dokumen. Ada banyak alasan, misalnya pembatasan lisensi atau ketika font yang diinginkan tidak ditemukan di komputer tujuan. Ketika situasi ini terjadi, tidak mudah untuk mendeteksi, karena font yang diinginkan disematkan melalui serangkaian properti bendera Font.IsEmbedded = true; Tentu saja, mungkin untuk membaca properti ini segera setelah diatur tetapi itu bukan pendekatan yang nyaman. Bendera NotifyAboutFontEmbeddingError memaksa mekanisme pengecualian untuk kasus ketika upaya untuk menyematkan font gagal. Jika bendera ini diatur, pengecualian tipe [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) akan dilemparkan. Secara default false. |

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)