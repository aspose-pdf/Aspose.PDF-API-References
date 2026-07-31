---
title: "Kelas TextSearchOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "kelas Aspose.Pdf.Text.TextSearchOptions. Mewakili opsi pencarian teks"
type: docs
weight: 11230
url: /id/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

Mewakili opsi pencarian teks

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Menginisialisasi instance baru dari objek `TextSearchOptions`. Menentukan mode penggunaan ekspresi reguler. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Menginisialisasi instance baru dari objek `TextSearchOptions`. Menentukan persegi panjang yang membatasi teks yang dicari. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Menginisialisasi instance baru dari objek `TextSearchOptions`. Menentukan persegi panjang yang membatasi teks yang dicari dan mode penggunaan ekspresi reguler. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan oleh penyerap teks (fragmen). true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false (default) - kesalahan ketidakhadiran font akan menghentikan pemrosesan dengan melemparkan pengecualian. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa fragmen teks yang mewakili bayangan teks normal akan diabaikan selama pencarian. true - berarti teks bayangan tidak akan ditemukan (coba ini jika pencarian teks mengembalikan fragmen duplikat pada posisi yang berdekatan) false - berarti teks bayangan akan ditemukan bersama teks normal (nilai default) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa ekspresi reguler digunakan. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa teks dicari dalam batas halaman. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa kesalahan ekstraksi teks (dekoding) akan dicatat dalam penyerap teks (fragmen). true - berarti kesalahan ekstraksi teks (dekoding) akan dicatat. Ini dapat menurunkan kinerja. false (default) - tidak ada pencatatan kesalahan. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Mendapatkan atau mengatur persegi panjang yang membatasi teks yang dicari. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Mendapatkan atau mengatur nilai yang memungkinkan pencarian grafik terkait teks (garis bawah, latar belakang, dll.) selama pencarian teks. true - pencarian grafik terkait teks akan dilakukan (nilai default). false - elemen grafik yang mungkin ada dalam dokumen sumber akan diabaikan. Atur ini jika ada masalah kinerja atau tidak perlu menangani garis bawah, latar belakang, atau pemotongan. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Mendapatkan atau mengatur nilai yang memungkinkan pencarian teks dalam Annotations. true - teks akan dicari dalam Annotations. false - teks dalam Annotations tidak akan diparse oleh TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Mendapatkan atau mengatur nilai yang membatasi pencarian grafik terkait teks (garis bawah, latar belakang, dll.) pada halaman untuk jumlah elemen yang ditentukan. Nilai default adalah 250. Atur nilai lebih kecil jika ada masalah kinerja, coba nilai lebih besar jika beberapa elemen grafik tidak ditemukan. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa teks akan dicari menggunakan enkoding mesin font. true - berarti enkoding mesin font akan digunakan (coba ini jika pencarian teks gagal karena enkoding yang tidak sempurna dalam dokumen) false - berarti enkoding font dokumen yang akan digunakan (nilai default) |

### Lihat Juga

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


