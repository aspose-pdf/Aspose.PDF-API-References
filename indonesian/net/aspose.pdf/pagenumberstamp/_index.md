---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PageNumberStamp. Mewakili cap nomor halaman dan digunakan untuk memberi nomor halaman
type: docs
weight: 8230
url: /id/net/aspose.pdf/pagenumberstamp/
---
## Kelas PageNumberStamp

Mewakili cap nomor halaman dan digunakan untuk memberi nomor halaman.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Menginisialisasi instance baru dari kelas `PageNumberStamp`. Format diatur ke "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Membuat PageNumberStamp dengan teks terformat. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Menginisialisasi instance baru dari kelas `PageNumberStamp`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Jika diaktifkan, ukuran font akan disesuaikan secara otomatis agar sesuai dengan persegi cap berukuran: [`Width`](../textstamp/width/) dan [`Height`](../textstamp/height/). Lebar dan tinggi default diambil dari persegi halaman. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mendapatkan nilai bool yang menunjukkan bahwa konten dicap sebagai latar belakang. Jika nilainya true, konten cap diletakkan di bawah. Secara default, nilainya false, konten cap diletakkan di atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mendapatkan atau mengatur margin bawah cap. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Properti ini menentukan bagaimana cap digambar di halaman. Jika Draw = true cap digambar sebagai operator grafis dan jika draw = false maka cap digambar sebagai teks. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Ukuran font aktual setelah cap ditempatkan. (Mungkin berbeda dari ukuran font awal yang diberikan melalui konstruktor jika opsi 'AutoAdjustFontSizeToFitStampRectangle' diaktifkan.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Nilai string untuk mencap nomor halaman. Nilai harus menyertakan karakter '#' yang digantikan dengan nomor halaman dalam proses pencap. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Tinggi yang diinginkan dari cap di halaman. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal cap di halaman. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua tepi kiri dan kanan teks akan disejajarkan. Nilai default: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mendapatkan atau mengatur margin kiri cap. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Tinggi baris maksimum untuk opsi WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Mendapatkan atau mengatur mode yang mendefinisikan perilaku jika font tidak mengandung karakter yang diminta. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Gaya penomoran yang digunakan oleh cap ini. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas cap. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas garis luar cap. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mendapatkan atau mengatur nilai lebar garis luar cap. Secara default, nilainya 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Mendapatkan atau mengatur font yang digunakan untuk menggantikan jika font pengguna tidak mengandung karakter yang diperlukan. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mendapatkan atau mengatur margin kanan cap. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mendapatkan rotasi konten cap sesuai dengan nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan dari 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut sembarang gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan dari 90 maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mendapatkan atau mengatur sudut rotasi cap dalam derajat. Properti ini memungkinkan untuk mengatur sudut rotasi sembarang. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Mendapatkan atau mengatur nilai nomor halaman awal. Halaman lain akan diberi nomor mulai dari nilai ini. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Perataan teks di dalam cap. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Mendapatkan properti teks dari cap. Lihat [`TextState`](../textstamp/textstate/) untuk detail. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mendapatkan atau mengatur margin atas cap. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default saat Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default saat Draw = false) nilai YIndent akan diperlakukan sebagai bawah (garis turunan) teks. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Mendapatkan atau mengatur nilai string yang digunakan sebagai cap di halaman. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal cap di halaman. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Lebar yang diinginkan dari cap di halaman. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Mendapatkan atau mengatur mode pembungkus kata untuk rendering teks. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Koordinat horizontal cap, dimulai dari kiri. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Koordinat vertikal cap, dimulai dari bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom dari cap. Memungkinkan untuk menskalakan cap. Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan untuk mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal dari cap. Memungkinkan untuk menskalakan cap secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal dari cap. Memungkinkan untuk menskalakan cap secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID cap. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Menambahkan nomor halaman. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID cap. |

### Lihat Juga

* kelas [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)