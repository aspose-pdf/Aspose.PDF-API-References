---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: Properti IFontOptions. Terkadang tidak mungkin untuk menyematkan font yang diinginkan ke dalam dokumen. Ada banyak alasan, misalnya pembatasan lisensi atau ketika font yang diinginkan tidak ditemukan di komputer tujuan. Ketika situasi ini muncul, tidak mudah untuk mendeteksi, karena font yang diinginkan disematkan melalui serangkaian bendera properti Font.IsEmbedded = true; Tentu saja, mungkin untuk membaca properti ini segera setelah diatur, tetapi itu bukan pendekatan yang nyaman. Bendera NotifyAboutFontEmbeddingError menerapkan mekanisme pengecualian untuk kasus ketika upaya untuk menyematkan font gagal. Jika bendera ini diatur, pengecualian tipe [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) akan dilemparkan. Secara default false.
type: docs
weight: 10
url: /id/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## Properti IFontOptions.NotifyAboutFontEmbeddingError

Terkadang tidak mungkin untuk menyematkan font yang diinginkan ke dalam dokumen. Ada banyak alasan, misalnya pembatasan lisensi atau ketika font yang diinginkan tidak ditemukan di komputer tujuan. Ketika situasi ini muncul, tidak mudah untuk mendeteksi, karena font yang diinginkan disematkan melalui serangkaian bendera properti Font.IsEmbedded = true; Tentu saja, mungkin untuk membaca properti ini segera setelah diatur, tetapi itu bukan pendekatan yang nyaman. Bendera NotifyAboutFontEmbeddingError menerapkan mekanisme pengecualian untuk kasus ketika upaya untuk menyematkan font gagal. Jika bendera ini diatur, pengecualian tipe [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) akan dilemparkan. Secara default false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Lihat Juga

* antarmuka [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)