---
title: "Kelas PageNumberStamp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.PageNumberStamp. Mewakili stempel nomor halaman dan digunakan untuk memberi nomor pada halaman"
type: docs
weight: 8370
url: /id/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Mewakili cap nomor halaman dan digunakan untuk memberi nomor pada halaman.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Menginisialisasi instance baru dari kelas `PageNumberStamp`. Format diatur ke "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Membuat PageNumberStamp dengan teks yang diformat. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Menginisialisasi instance baru dari kelas `PageNumberStamp`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Jika diaktifkan, ukuran font akan secara otomatis disesuaikan untuk memenuhi persegi panjang stempel dengan ukuran: [`Width`](../textstamp/width/) dan [`Height`](../textstamp/height/). Lebar dan tinggi default diambil dari persegi panjang halaman. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mengambil nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mengambil atau mengatur margin bawah stempel. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Properti ini menentukan bagaimana stempel digambar pada page. Jika Draw = true, stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Ukuran font aktual setelah stempel ditempatkan. (Mungkin berbeda dari ukuran font awal yang diberikan melalui konstruktor jika opsi 'AutoAdjustFontSizeToFitStampRectangle' diaktifkan.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Nilai string untuk menstempel nomor halaman. Nilai harus menyertakan karakter '#' yang akan diganti dengan nomor halaman selama proses penstempelan. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Tinggi yang diinginkan untuk stempel pada halaman. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mengambil atau mengatur perataan horizontal stempel pada halaman. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Mendefinisikan perataan teks. Jika properti ini disetel ke true, kedua tepi kiri dan kanan teks akan rata. Nilai default: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mengambil atau mengatur margin kiri stempel. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Tinggi baris maksimum untuk opsi WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Mendapatkan atau mengatur mode yang menentukan perilaku bila font tidak mengandung karakter yang diminta. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Gaya penomoran yang digunakan oleh stempel ini. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mengambil atau mengatur nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mengambil atau mengatur nilai untuk menunjukkan opasitas garis tepi stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mengambil atau mengatur nilai lebar garis tepi stempel. Secara default nilai adalah 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Mendapatkan atau mengatur font yang digunakan untuk mengganti jika font pengguna tidak mengandung karakter yang diperlukan. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mengambil atau mengatur margin kanan stempel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mengambil rotasi konten stempel sesuai nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mengambil atau mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan pengaturan sudut rotasi arbitrer. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Mendefinisikan skala teks. Jika properti ini disetel ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Mendapatkan atau mengatur nilai nomor halaman awal. Halaman lainnya akan diberi nomor mulai dari nilai ini. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Perataan teks di dalam stempel. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Mendapatkan properti teks dari stempel. Lihat [`TextState`](../textstamp/textstate/) untuk detail. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mengambil atau mengatur margin atas stempel. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default ketika Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default ketika Draw = false) nilai YIndent akan diperlakukan sebagai bagian bawah (garis turun) teks. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Mendapatkan atau mengatur nilai string yang digunakan sebagai stempel pada halaman. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mengambil atau mengatur perataan vertikal stempel pada halaman. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Lebar yang diinginkan untuk stempel pada halaman. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Mendapatkan atau mengatur mode pembungkus kata untuk rendering teks. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Koordinat horizontal stempel, dimulai dari kiri. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Koordinat stempel vertikal, dimulai dari bagian bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom stempel. Memungkinkan memperbesar/memperkecil stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal stempel. Memungkinkan memperbesar/memperkecil stempel secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal stempel. Memungkinkan memperbesar/memperkecil stempel secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID stempel. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Menambahkan nomor halaman. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID stempel. |

### Lihat Juga

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


