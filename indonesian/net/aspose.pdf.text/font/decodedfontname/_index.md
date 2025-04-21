---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Properti font. Terkadang font PDF, biasanya font Cina/Jepang/Korea, dapat memiliki nama font tertentu. Nama ini adalah nilai dari properti font PDF "BaseFont" dan terkadang properti ini dapat direpresentasikan dalam bentuk heksadesimal. Jika membaca nama ini secara langsung, itu dapat direpresentasikan dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, perlu untuk mendekode nama font dengan aturan yang spesifik untuk font ini. Properti ini mengembalikan nama font yang telah didekode, jadi gunakan ini untuk kasus ketika Anda menemui [`FontName`](../fontname/) yang tidak dapat dibaca. Jika properti [`FontName`](../fontname/) memiliki bentuk yang dapat dibaca, properti ini akan sama dengan [`FontName`](../fontname/), jadi Anda dapat menggunakan properti ini untuk kasus apa pun ketika Anda perlu mendapatkan nama font dalam bentuk yang dapat dibaca.
type: docs
weight: 20
url: /id/net/aspose.pdf.text/font/decodedfontname/
---
## Properti Font.DecodedFontName

Terkadang font PDF (biasanya font Cina/Jepang/Korea) dapat memiliki nama font tertentu. Nama ini adalah nilai dari properti font PDF "BaseFont" dan terkadang properti ini dapat direpresentasikan dalam bentuk heksadesimal. Jika membaca nama ini secara langsung, itu dapat direpresentasikan dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, perlu untuk mendekode nama font dengan aturan yang spesifik untuk font ini. Properti ini mengembalikan nama font yang telah didekode, jadi gunakan ini untuk kasus ketika Anda menemui [`FontName`](../fontname/) yang tidak dapat dibaca. Jika properti [`FontName`](../fontname/) memiliki bentuk yang dapat dibaca, properti ini akan sama dengan [`FontName`](../fontname/), jadi Anda dapat menggunakan properti ini untuk kasus apa pun ketika Anda perlu mendapatkan nama font dalam bentuk yang dapat dibaca.

```csharp
public string DecodedFontName { get; }
```

### Lihat Juga

* kelas [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)