---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti IFontOptions. Terkadang tidak memungkinkan untuk menyematkan font yang diinginkan ke dalam dokumen. Ada banyak alasan, misalnya pembatasan lisensi atau ketika font yang diinginkan tidak ditemukan di komputer tujuan. Ketika situasi ini terjadi, tidak mudah dideteksi karena font yang diinginkan disematkan melalui flag properti Font.IsEmbedded = true. Tentu saja properti ini dapat dibaca segera setelah diatur, tetapi pendekatannya tidak praktis. Flag NotifyAboutFontEmbeddingError memberlakukan mekanisme pengecualian untuk kasus ketika upaya menyematkan font gagal. Jika flag ini diatur, pengecualian bertipe FontEmbeddingException akan dilempar. Secara default false."
type: docs
weight: 10
url: /id/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

Terkadang tidak memungkinkan untuk menyematkan font yang diinginkan ke dalam dokumen. Ada banyak alasan, misalnya pembatasan lisensi atau ketika font yang diinginkan tidak ditemukan di komputer tujuan. Ketika situasi ini terjadi, tidak mudah dideteksi, karena font yang diinginkan disematkan melalui flag properti Font.IsEmbedded = true; Tentu saja properti ini dapat dibaca segera setelah diatur, tetapi pendekatannya tidak praktis. Flag NotifyAboutFontEmbeddingError memberlakukan mekanisme pengecualian untuk kasus ketika upaya menyematkan font gagal. Jika flag ini diatur, pengecualian bertipe [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) akan dilempar. Secara default false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Lihat Juga

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


