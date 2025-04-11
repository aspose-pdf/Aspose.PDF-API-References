---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.EpubSaveOptionsRecognitionMode. Ketika file PDF yang biasanya memiliki tata letak tetap sedang dikonversi, mesin konversi mencoba melakukan pengelompokan dan analisis multilevel untuk mengembalikan niat asli penulis dokumen dan menghasilkan hasil dalam tata letak aliran. Properti ini mengatur konversi tersebut untuk metode pengenalan konten yang diinginkan.
type: docs
weight: 4070
url: /id/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## Enumerasi EpubSaveOptions.RecognitionMode

Ketika file PDF (yang biasanya memiliki tata letak tetap) sedang dikonversi, mesin konversi mencoba melakukan pengelompokan dan analisis multi-level untuk mengembalikan niat asli penulis dokumen dan menghasilkan hasil dalam tata letak aliran. Properti ini mengatur konversi tersebut untuk metode pengenalan konten yang diinginkan.

```csharp
public enum RecognitionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Flow | `0` | Mode pengenalan penuh, mesin mencoba melakukan pengelompokan dan analisis multi-level untuk mengembalikan niat asli penulis dokumen dan menghasilkan xhtml dalam tata letak aliran. |
| PdfFlow | `1` | Ide utama dari konversi ini didasarkan pada menyimpan urutan "alami" dari rendering konten yang terbentuk selama pemrosesan dokumen pdf. Dalam kasus umum, dokumen pdf mempertahankan urutan rendering dari atas ke bawah, kiri ke kanan (lihat arah lampiran directions.png). Asumsi ini memungkinkan untuk membuat algoritma jalur tunggal yang akan mengubah elemen Aps yang memiliki posisi (tata letak tetap) menjadi format aliran seperti HTML, EPUB, DOC. Mode ini akan sangat berguna untuk mengonversi dari PDF(APS) ke EPUB, karena format EPUB dikembangkan untuk pembaca e-book seperti Kindle atau smartphone. Ukuran layar perangkat tersebut biasanya lebih kecil daripada ukuran layar PC biasa. Oleh karena itu, konten dokumen EPUB lebih baik disimpan dalam format aliran, untuk rendering yang benar pada layar dengan ukuran yang berbeda. Dalam mode ini, setiap kolom akan ditambahkan ke akhir kolom sebelumnya, ini memungkinkan untuk menjaga struktur logis dokumen yang diubah selama "paginasi" di pembaca EPUB. Pencapaian ini memungkinkan untuk merender artikel ilmiah atau majalah dengan benar. |
| Fixed | `2` | Mode ini cepat dan baik untuk memaksimalkan pelestarian tampilan asli halaman, tetapi sayangnya banyak pembaca EPUB tidak mendukung xhtml dengan tata letak tetap |

### Lihat Juga

* kelas [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)