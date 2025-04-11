---
title: Class PaginationArtifact
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PaginationArtifact. Mewakili kelas dasar abstrak untuk artefak pagination dalam dokumen
type: docs
weight: 8260
url: /id/net/aspose.pdf/paginationartifact/
---
## Kelas PaginationArtifact

Mewakili kelas dasar abstrak untuk artefak pagination dalam dokumen.

```csharp
public abstract class PaginationArtifact : Artifact
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Penjajaran horizontal artefak. Jika posisi ditentukan secara eksplisit (dalam properti Posisi) nilai ini diabaikan. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Penjajaran vertikal artefak. Jika posisi ditentukan secara eksplisit (dalam properti Posisi) nilai ini diabaikan. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margin bawah artefak. Jika posisi ditentukan secara eksplisit (dalam properti Posisi) nilai ini diabaikan. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Mendapatkan koleksi operator internal artefak. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Mendapatkan nama subtipe artefak. Dapat digunakan jika subtipe artefak bukan subtipe standar. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Mendapatkan nama tipe artefak. Dapat digunakan jika tipe artefak bukan standar. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Mendapatkan atau mengatur nomor halaman akhir untuk artefak. Nilai harus lebih besar dari atau sama dengan 0. Jika nilai kurang dari 0 diatur, itu akan disesuaikan menjadi 0. Nilai default 0 berarti tidak ada batasan halaman akhir. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Mendapatkan XForm dari artefak (jika XForm digunakan). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Mendapatkan gambar dari artefak (jika ada). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Jika benar, Artefak ditempatkan di belakang konten halaman. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margin kiri artefak. Jika posisi ditentukan secara eksplisit (dalam properti Posisi) nilai ini diabaikan. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Baris teks multiline artefak. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas artefak. Nilai yang mungkin berada dalam rentang 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Mendapatkan atau mengatur posisi artefak. Jika properti ini ditentukan, maka margin dan penjajaran diabaikan. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Mendapatkan persegi panjang dari artefak. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margin kanan artefak. Jika posisi ditentukan secara eksplisit (dalam properti Posisi) nilai ini diabaikan. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Mendapatkan atau mengatur sudut rotasi artefak. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Mendapatkan atau mengatur nomor halaman awal untuk artefak. Nilai harus lebih besar dari atau sama dengan 1. Jika nilai kurang dari 1 diatur, itu akan disesuaikan menjadi 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Mendapatkan atau mengatur subset halaman yang diterapkan artefak (misalnya, semua halaman, halaman genap, halaman ganjil). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Mendapatkan subtipe artefak. Jika artefak memiliki subtipe non-standar, nama subtipe dapat dibaca melalui CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Mendapatkan teks dari artefak. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Status teks untuk teks artefak. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margin atas artefak. Jika posisi ditentukan secara eksplisit (dalam properti Posisi) nilai ini diabaikan. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Mendapatkan tipe artefak. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Mulai pembaruan yang tertunda. Gunakan fitur ini jika Anda perlu melakukan beberapa perubahan pada artefak yang sama untuk meningkatkan kinerja. Biasanya operator artefak diubah setiap kali properti artefak diubah. Ini menyebabkan perubahan konten halaman setiap kali artefak diubah. Untuk menghindari efek ini, letakkan semua pembaruan artefak di antara panggilan StartUpdates/SaveUpdates. Ini memungkinkan untuk mengubah konten halaman hanya sekali. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Buang artefak. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Mendapatkan nilai kustom dari artefak. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Menghapus nilai kustom dari artefak. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Menyimpan semua pembaruan dalam artefak yang dilakukan setelah panggilan BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Mengatur gambar dari artefak. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Mengatur gambar dari artefak. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Mengatur teks dan properti teks dari artefak. Memungkinkan untuk menentukan beberapa baris. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Mengatur string apa yang akan diganti dengan nomor halaman. Nilai default adalah #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Mengatur halaman PDF yang ditempatkan di halaman dokumen sebagai artefak. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Mengatur teks dari artefak. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Mengatur teks dan properti teks dari artefak. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Mengatur nilai kustom dari artefak. |

### Lihat Juga

* kelas [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)