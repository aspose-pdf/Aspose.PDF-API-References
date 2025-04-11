---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Page. Kelas yang mewakili halaman dokumen PDF
type: docs
weight: 8050
url: /id/net/aspose.pdf/page/
---
## Kelas Halaman

Kelas yang mewakili halaman dokumen PDF.

```csharp
public sealed class Page : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Mendapatkan koleksi properti halaman. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Mendapatkan koleksi anotasi halaman. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Mendapatkan atau mengatur kotak seni halaman. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Mendapatkan koleksi artefak di halaman. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Mendapatkan atau mengatur warna latar belakang halaman. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Mendapatkan atau mengatur kotak bleed halaman. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Mengatur jenis warna halaman berdasarkan informasi yang diperoleh dari operator SetColor, gambar, dan formulir. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Mendapatkan koleksi operator dalam aliran konten halaman. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Mendapatkan atau mengatur kotak crop halaman. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Mendapatkan atau mengatur durasi tampilan halaman. Ini adalah waktu dalam detik bahwa halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak ditentukan. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Mendapatkan daftar objek Field dalam urutan Tab di halaman ini. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Mendapatkan atau mengatur footer halaman. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Mendapatkan atau mengatur kelas atribut grup yang menentukan atribut grup halaman untuk digunakan dalam model pencitraan transparan. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Mendapatkan atau mengatur header halaman. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Mendapatkan atau mengatur penambahan paragraf setelah paragraf terakhir halaman |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Mendapatkan atau mengatur koleksi lapisan. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Mendapatkan atau mengatur kotak media halaman. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Mendapatkan atau mengatur gaya garis untuk catatan. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [Number](../../aspose.pdf/page/number/) { get; } | Mendapatkan nomor halaman. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Mendapatkan atau mengatur informasi halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Mendapatkan paragraf. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang halaman. Untuk mendapatkan: kotak crop halaman dikembalikan jika ditentukan, jika tidak kotak media halaman dikembalikan. Untuk mengatur: kotak media halaman selalu diatur. Harap dicatat bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, harap gunakan ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Mendapatkan sumber daya halaman. Objek sumber daya berisi koleksi gambar, formulir, dan font. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Mendapatkan atau mengatur rotasi halaman. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Mendapatkan matriks transformasi untuk halaman. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Mendapatkan atau mengatur urutan tab halaman. Nilai yang mungkin: Baris, Kolom. Default, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Mendapatkan atau mengatur informasi daftar isi. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Mendapatkan atau mengatur kotak trim halaman. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Mendapatkan atau mengatur nilai UserUnit. Sebuah angka positif yang memberikan ukuran unit ruang pengguna default, dalam kelipatan 1 / 72 inci. Nilai default adalah 1. Harap atur nilai nol atau negatif untuk menghapus entri ini di halaman. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Mendapatkan atau mengatur watermark halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Menerima objek pengunjung [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) yang menyediakan fungsionalitas untuk bekerja dengan anotasi. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Menerima objek pengunjung [`ImagePlacementAbsorber`](../imageplacementabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Menerima objek pengunjung [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Menerima objek pengunjung [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Menambahkan grafik ke halaman. Bekerja lebih cepat daripada menambahkan elemen satu per satu dengan metode [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Menambahkan gambar ke halaman dan menempatkannya tergantung pada posisi persegi panjang gambar. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Menempatkan stempel ke dalam halaman. Stempel bisa berupa nomor halaman, gambar, atau teks sederhana, misalnya, beberapa logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Mengonversi halaman saat ini sebagai bitmap dan kemudian mengembalikan array byte. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Mengonversi halaman saat ini sebagai xml dalam encoding utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Menghitung nilai bbox - persegi panjang yang berisi konten tanpa margin yang terlihat. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Mengonversi halaman ke PNG untuk aliran gambar DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Menghapus grafik dari halaman. Bekerja lebih cepat daripada menghapus elemen satu per satu dengan metode [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Membebaskan memori |
| [Flatten](../../aspose.pdf/page/flatten/)() | Menghapus semua bidang yang terletak di halaman dan menempatkan nilai mereka sebagai gantinya. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Menghapus data yang di-cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Mengembalikan notifikasi tentang operasi di dalam konten halaman. (Hanya notifikasi tentang peristiwa paragraf dalam skenario penambahan teks yang didukung saat ini.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Mengembalikan persegi panjang halaman sesuai dengan CropBox-nya (atau MediaBox jika CropBox null). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Mengambil sumber daya yang terkait dengan halaman. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Mendeteksi keberadaan grafik vektor, jika ada di halaman. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Mendapatkan tanda apakah halaman kosong atau tidak. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Mengonversi halaman menjadi grayscale. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Menggabungkan semua lapisan di halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Menggabungkan semua lapisan di halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan dan ID grup konten opsional. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Mengubah ukuran halaman. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Mengatur ukuran halaman untuk halaman. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Mencoba menyimpan grafik vektor jika ada di halaman. Format simpan adalah SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Menerjemahkan nilai integer menjadi anggota enumerasi rotasi yang sesuai. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Menerjemahkan anggota enumerasi rotasi menjadi nilai integer. |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Peristiwa untuk menyesuaikan header dan footer. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Prosedur untuk menyesuaikan header dan footer. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)