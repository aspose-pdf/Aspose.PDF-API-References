---
title: "Enum ExplicitDestinationType"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Annotations.ExplicitDestinationType. Mendaftar jenis-jenis tujuan eksplisit."
type: docs
weight: 1780
url: /id/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumeration

Menumerasikan tipe-tipe tujuan eksplisit.

```csharp
public enum ExplicitDestinationType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| XYZ | `0` | Tampilkan halaman dengan koordinat (left, top) diposisikan di sudut kiri atas jendela dan isi halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter left, top, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. Nilai zoom 0 memiliki arti yang sama dengan nilai null. |
| Fit | `1` | Tampilkan halaman dengan isinya diperbesar cukup untuk menampung seluruh halaman dalam jendela secara horizontal dan vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan halaman dalam jendela pada dimensi lainnya. |
| FitH | `2` | Tampilkan halaman dengan koordinat vertikal top diposisikan di tepi atas jendela dan isi halaman diperbesar cukup untuk menampung lebar seluruh halaman dalam jendela. Nilai null untuk top menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. |
| FitV | `3` | Tampilkan halaman dengan koordinat horizontal left diposisikan di tepi kiri jendela dan isi halaman diperbesar cukup untuk menampung tinggi seluruh halaman dalam jendela. Nilai null untuk left menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. |
| FitR | `4` | Tampilkan halaman dengan isinya diperbesar cukup untuk menampung persegi panjang yang ditentukan oleh koordinat left, bottom, right, dan topentirely dalam jendela secara horizontal dan vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan persegi panjang dalam jendela pada dimensi lainnya. Nilai null untuk salah satu parameter dapat menghasilkan perilaku yang tidak dapat diprediksi. |
| FitB | `5` | Tampilkan halaman dengan isinya diperbesar cukup untuk menampung bounding box-nya sepenuhnya dalam jendela secara horizontal dan vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan bounding box dalam jendela pada dimensi lainnya. |
| FitBH | `6` | Tampilkan halaman dengan koordinat vertikal top diposisikan di tepi atas jendela dan isi halaman diperbesar cukup untuk menampung lebar penuh bounding box-nya dalam jendela. Nilai null untuk top menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. |
| FitBV | `7` | Tampilkan halaman dengan koordinat horizontal left diposisikan di tepi kiri jendela dan isi halaman diperbesar cukup untuk menampung tinggi penuh bounding box-nya dalam jendela. Nilai null untuk left menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. |

### Lihat Juga

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


