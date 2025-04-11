---
title: Class FileSelectBoxField
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Forms.FileSelectBoxField. Field untuk elemen kotak pilih file
type: docs
weight: 5060
url: /id/net/aspose.pdf.forms/fileselectboxfield/
---
## Kelas FileSelectBoxField

Field untuk elemen kotak pilih file.

```csharp
public sealed class FileSelectBoxField : TextBoxField
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Mendapatkan aksi anotasi. (2 properti) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau mengatur status tampilan anotasi saat ini. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Mendapatkan atau mengatur nama alternatif dari field (Nama field alternatif yang akan digunakan sebagai pengganti nama field yang sebenarnya di mana pun field tersebut diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip field di Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Mendapatkan atau mengatur indeks anotasi ini di halaman. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Mendapatkan jenis anotasi. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus tampilan dari anotasi. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau mengatur karakteristik batas anotasi. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik anotasi. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau mengatur warna anotasi. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau mengatur teks anotasi. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Mendapatkan jumlah subfield dalam field ini. (Misalnya jumlah item dalam field tombol radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Mendapatkan atau mengatur tampilan default dari field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Mendapatkan atau mengatur flag dapat diekspor dari field. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dari anotasi. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Mendapatkan atau mengatur flag yang menunjukkan apakah field dibagi menjadi posisi yang terpisah. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari anotasi. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau mengatur tinggi anotasi. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Mode penyorotan anotasi. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah field ini adalah field non-terminal yaitu kelompok field. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Properti untuk dukungan Generator. Digunakan ketika field ditambahkan ke header atau footer. Jika true, field ini akan dibuat sekali dan tampilannya akan terlihat di semua halaman dokumen. Jika false, field terpisah akan dibuat untuk setiap halaman dokumen. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Mengembalikan true jika kamus disinkronkan. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Mendapatkan subfield yang terkandung dalam field ini berdasarkan nama subfield. (2 indeks) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Mendapatkan atau mengatur nama pemetaan dari field yang akan digunakan saat mengekspor data field formulir interaktif dari dokumen. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk generasi pdf) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Mendapatkan atau mengatur panjang maksimum teks dalam field. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau mengatur tanggal dan waktu ketika anotasi terakhir kali dimodifikasi. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Mendapatkan atau mengatur flag multiline dari field. Jika Multiline adalah true, field dapat berisi beberapa baris teks. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau mengatur nama anotasi di halaman. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Aksi yang akan dilakukan ketika anotasi diaktifkan. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi field ini. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Mendapatkan induk anotasi. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Mendapatkan atau mengatur nama parsial dari field. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Mendapatkan atau mengatur status hanya-baca dari field. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang field. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Mendapatkan atau mengatur status diperlukan dari field. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Mendapatkan atau mengatur flag dapat digulir dari field. Jika true, field dapat digulir. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Mendapatkan atau mengatur flag pemeriksaan ejaan untuk field. Jika true, field akan diperiksa ejaannya. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus tampilan dari anotasi. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objek sinkronisasi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Mendapatkan atau mengatur urutan tab dari field. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal teks untuk anotasi. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Mendapatkan atau mengatur nilai dari field. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau mengatur lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Menerima pengunjung. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Menambahkan barcode 128 ke dalam field. Nilai field akan diubah menjadi kode dan field menjadi hanya-baca. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | Menambahkan gambar ke dalam sumber daya field dan menggambarnya. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Menyalin subfield dari field ini ke dalam array mulai dari indeks yang ditentukan. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Menjalankan aksi JavaScript yang ditentukan untuk field. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Mengekspor field formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke stream yang disediakan. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Mengekspor field formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke file yang ditentukan. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Mengekspor konten dari field yang ditentukan ke dalam stream JSON. Nilai field tombol tidak diekspor. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Menghapus field ini dan menempatkan nilainya langsung di halaman. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mengembalikan nama status "tercentang" sesuai dengan nama status yang ada. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Mengembalikan enumerator dari field yang terkandung. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Mengimpor data ke dalam field yang ditentukan dari stream JSON, berdasarkan kecocokan nama lengkap field yang tepat. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Mengimpor data ke dalam field yang ditentukan dari stream JSON, menggunakan nama lengkap yang ditentukan dalam variabel 'fieldFullNameInJSON' untuk pencocokan. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Menghitung ulang semua field yang dihitung pada formulir. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Mengatur posisi field. |

### Lihat Juga

* kelas [TextBoxField](../textboxfield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)