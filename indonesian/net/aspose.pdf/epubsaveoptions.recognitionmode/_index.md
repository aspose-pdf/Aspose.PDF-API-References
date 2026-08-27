---
title: "Enum EpubSaveOptions.RecognitionMode"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.EpubSaveOptionsRecognitionMode. Ketika file PDF yang biasanya memiliki tata letak tetap dikonversi, mesin konversi berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan hasil dalam tata letak aliran. Properti ini menyesuaikan konversi tersebut untuk metode pengenalan konten yang diinginkan."
type: docs
weight: 4190
url: /id/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

Ketika file PDF (yang biasanya memiliki tata letak tetap) sedang dikonversi, mesin konversi berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan hasil dalam tata letak aliran. Properti ini menyesuaikan konversi tersebut untuk metode pengenalan konten yang diinginkan.

```csharp
public enum RecognitionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Flow | `0` | Mode pengenalan penuh, mesin berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan XHTML dalam tata letak aliran. |
| PdfFlow | `1` | Ide utama konversi ini didasarkan pada penyimpanan urutan \"alami\" rendering konten yang terbentuk selama pemrosesan dokumen pdf. Pada umumnya dokumen pdf mempertahankan urutan rendering atas‑bawah, kiri‑kanan (lihat lampiran directions.png). Asumsi ini memungkinkan pembuatan algoritma jalur tunggal yang akan mengubah elemen Aps yang memiliki posisi (tata letak tetap) menjadi format aliran seperti HTML, EPUB, DOC. Mode ini akan sangat berguna untuk mengonversi dari PDF (APS) ke EPUB, karena format EPUB dikembangkan untuk e‑reader seperti Kindle atau ponsel pintar. Ukuran layar perangkat tersebut biasanya lebih kecil daripada layar PC biasa. Oleh karena itu konten dokumen EPUB lebih baik disimpan dalam format aliran, untuk rendering yang tepat pada layar dengan ukuran berbeda. Dalam mode ini setiap kolom akan ditambahkan ke akhir kolom sebelumnya, yang memungkinkan mempertahankan struktur logis dokumen yang diubah selama \"paginasi\" di pembaca EPUB. Pencapaian ini memungkinkan rendering yang tepat untuk artikel ilmiah atau majalah. |
| Fixed | `2` | Mode ini cepat dan baik untuk mempertahankan tampilan asli halaman secara maksimal, tetapi sayangnya banyak pembaca EPUB tidak mendukung XHTML dengan tata letak tetap. |

### Lihat Juga

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


