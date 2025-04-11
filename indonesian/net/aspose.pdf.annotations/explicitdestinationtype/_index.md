---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Annotations.ExplicitDestinationType. Mengenumerasi jenis tujuan eksplisit
type: docs
weight: 1690
url: /id/net/aspose.pdf.annotations/explicitdestinationtype/
---
## Enumerasi ExplicitDestinationType

Mengenumerasi jenis tujuan eksplisit.

```csharp
public enum ExplicitDestinationType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| XYZ | `0` | Tampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan konten halaman diperbesar dengan faktor zoom. Nilai null untuk parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. Nilai zoom 0 memiliki arti yang sama dengan nilai null. |
| Fit | `1` | Tampilkan halaman dengan kontennya diperbesar cukup untuk menyesuaikan seluruh halaman dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil dari keduanya, memusatkan halaman dalam jendela di dimensi lainnya. |
| FitH | `2` | Tampilkan halaman dengan koordinat vertikal atas diposisikan di tepi atas jendela dan konten halaman diperbesar cukup untuk menyesuaikan seluruh lebar halaman dalam jendela. Nilai null untuk atas menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| FitV | `3` | Tampilkan halaman dengan koordinat horizontal kiri diposisikan di tepi kiri jendela dan konten halaman diperbesar cukup untuk menyesuaikan seluruh tinggi halaman dalam jendela. Nilai null untuk kiri menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| FitR | `4` | Tampilkan halaman dengan kontennya diperbesar cukup untuk menyesuaikan persegi panjang yang ditentukan oleh koordinat kiri, bawah, kanan, dan atas sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil dari keduanya, memusatkan persegi panjang dalam jendela di dimensi lainnya. Nilai null untuk parameter mana pun dapat menghasilkan perilaku yang tidak terduga. |
| FitB | `5` | Tampilkan halaman dengan kontennya diperbesar cukup untuk menyesuaikan kotak batasnya sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil dari keduanya, memusatkan kotak batas dalam jendela di dimensi lainnya. |
| FitBH | `6` | Tampilkan halaman dengan koordinat vertikal atas diposisikan di tepi atas jendela dan konten halaman diperbesar cukup untuk menyesuaikan seluruh lebar kotak batasnya dalam jendela. Nilai null untuk atas menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| FitBV | `7` | Tampilkan halaman dengan koordinat horizontal kiri diposisikan di tepi kiri jendela dan konten halaman diperbesar cukup untuk menyesuaikan seluruh tinggi kotak batasnya dalam jendela. Nilai null untuk kiri menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |

### Lihat Juga

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)