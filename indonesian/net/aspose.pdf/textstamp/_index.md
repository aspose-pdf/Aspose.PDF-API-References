---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.TextStamp. Mewakili stempel tekstual
type: docs
weight: 11080
url: /id/net/aspose.pdf/textstamp/
---
## Kelas TextStamp

Mewakili stempel tekstual.

```csharp
public class TextStamp : Stamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | Menginisialisasi instance baru dari kelas `TextStamp` dengan objek formattedText |
| [TextStamp](textstamp/#constructor_1)(string) | Menginisialisasi instance baru dari kelas `TextStamp`. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | Menginisialisasi instance baru dari kelas `TextStamp`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Jika diaktifkan, ukuran font akan disesuaikan secara otomatis agar sesuai dengan persegi panjang stempel berukuran: [`Width`](./width/) dan [`Height`](./height/). Lebar dan tinggi default diambil dari persegi panjang halaman. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mendapatkan nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilainya true, konten stempel diletakkan di bawah. Secara default, nilainya false, konten stempel diletakkan di atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mendapatkan atau mengatur margin bawah stempel. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Properti ini menentukan bagaimana stempel digambar di halaman. Jika Draw = true stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Ukuran font aktual setelah stempel ditempatkan. (Mungkin berbeda dari ukuran font awal yang diberikan melalui konstruktor jika opsi 'AutoAdjustFontSizeToFitStampRectangle' diaktifkan.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Tinggi yang diinginkan dari stempel di halaman. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal stempel di halaman. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua tepi kiri dan kanan teks akan sejajar. Nilai default: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mendapatkan atau mengatur margin kiri stempel. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Tinggi baris maksimum untuk opsi WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Mendapatkan atau mengatur mode yang mendefinisikan perilaku jika font tidak mengandung karakter yang diminta. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas stempel. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya adalah 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas garis besar stempel. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya adalah 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mendapatkan atau mengatur nilai lebar garis besar stempel. Secara default, nilainya adalah 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Mendapatkan atau mengatur font yang digunakan untuk menggantikan jika font pengguna tidak mengandung karakter yang diperlukan. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mendapatkan atau mengatur margin kanan stempel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mendapatkan rotasi konten stempel sesuai dengan nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan dari 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut sembarang gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan dari 90 maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mendapatkan atau mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan untuk mengatur sudut rotasi sembarang. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Perataan teks di dalam stempel. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Mendapatkan properti teks dari stempel. Lihat [`TextState`](./textstate/) untuk detail. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mendapatkan atau mengatur margin atas stempel. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default saat Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default saat Draw = false) nilai YIndent akan diperlakukan sebagai bawah (garis turunan) teks. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Mendapatkan atau mengatur nilai string yang digunakan sebagai stempel di halaman. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal stempel di halaman. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Lebar yang diinginkan dari stempel di halaman. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Mendapatkan atau mengatur mode pembungkus kata untuk rendering teks. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Koordinat horizontal stempel, dimulai dari kiri. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Koordinat vertikal stempel, dimulai dari bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom dari stempel. Memungkinkan untuk menskalakan stempel. Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan untuk mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal dari stempel. Memungkinkan untuk menskalakan stempel secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal dari stempel. Memungkinkan untuk menskalakan stempel secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID stempel. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | Menambahkan stempel tekstual di halaman. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID stempel. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | Tindakan yang dilakukan jika font tidak mengandung karakter yang diperlukan. |

### Lihat Juga

* kelas [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)