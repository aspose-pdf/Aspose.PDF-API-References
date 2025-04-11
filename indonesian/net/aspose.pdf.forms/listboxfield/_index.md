---
title: Class ListBoxField
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Forms.ListBoxField. Kelas ini mewakili bidang ListBox
type: docs
weight: 5130
url: /id/net/aspose.pdf.forms/listboxfield/
---
## Kelas ListBoxField

Kelas ini mewakili bidang ListBox.

```csharp
public sealed class ListBoxField : ChoiceField
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ListBoxField](listboxfield/#constructor)() | Konstruktor untuk ListBoxField yang akan digunakan dalam Generator. |
| [ListBoxField](listboxfield/#constructor_1)(Dokumen, Rectangle) | Konstruktor untuk bidang ListBox. |
| [ListBoxField](listboxfield/#constructor_2)(Halaman, Rectangle) | Membuat bidang ListBox baru. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Mendapatkan tindakan anotasi. (2 properti) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau menetapkan status tampilan anotasi saat ini. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Mendapatkan atau menetapkan nama alternatif dari bidang (Nama bidang alternatif yang akan digunakan sebagai pengganti nama bidang yang sebenarnya di mana pun bidang tersebut diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip bidang di Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Mendapatkan atau menetapkan indeks anotasi ini di halaman. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Mendapatkan jenis anotasi. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus tampilan dari anotasi. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau menetapkan karakteristik batas anotasi. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik anotasi. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau menetapkan warna anotasi. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Mendapatkan atau menetapkan bendera komitmen pada perubahan pemilihan. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau menetapkan teks anotasi. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Mendapatkan jumlah subbidang dalam bidang ini. (Misalnya jumlah item dalam bidang tombol radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Mendapatkan atau menetapkan tampilan default dari bidang. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Mendapatkan atau menetapkan bendera dapat diekspor dari bidang. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Bendera dari anotasi. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap dari anotasi. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau menetapkan tinggi anotasi. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Mode penyorotan anotasi. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau menetapkan hyperlink fragmen (untuk generator pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah bidang ini adalah bidang non-terminal yaitu kelompok bidang. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau menetapkan paragraf sebagai inline. Default adalah false. (untuk pembuatan pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk pembuatan pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Properti untuk dukungan Generator. Digunakan ketika bidang ditambahkan ke header atau footer. Jika true, bidang ini akan dibuat sekali dan tampilannya akan terlihat di semua halaman dokumen. Jika false, bidang terpisah akan dibuat untuk setiap halaman dokumen. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Mengembalikan true jika kamus disinkronkan. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Mendapatkan subbidang yang terkandung dalam bidang ini berdasarkan nama subbidang. (2 indeks) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Mendapatkan atau menetapkan nama pemetaan dari bidang yang akan digunakan saat mengekspor data bidang formulir interaktif dari dokumen. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau menetapkan margin luar untuk paragraf (untuk pembuatan pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau menetapkan tanggal dan waktu ketika anotasi terakhir kali dimodifikasi. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Mendapatkan atau menetapkan bendera multiselection. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau menetapkan nama anotasi di halaman. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Tindakan yang akan dilakukan ketika anotasi diaktifkan. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Mendapatkan koleksi opsi pilihan. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi bidang ini. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Mendapatkan induk anotasi. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Mendapatkan atau menetapkan nama parsial dari bidang. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Mendapatkan atau menetapkan status hanya baca dari bidang. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Mendapatkan atau menetapkan persegi panjang bidang. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Mendapatkan atau menetapkan status diperlukan dari bidang. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected/) { set; } | Mendapatkan atau menetapkan indeks item yang dipilih. Item diberi nomor mulai dari 1. |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems/) { set; } | Mendapatkan atau menetapkan array item yang dipilih dalam daftar multiselect. Untuk daftar pemilihan tunggal mengembalikan array dengan satu item. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus tampilan dari anotasi. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objek sinkronisasi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Mendapatkan atau menetapkan urutan tab dari bidang. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan teks untuk anotasi. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex/) { get; set; } | Mendapatkan atau menetapkan indeks elemen teratas yang terlihat dari daftar. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Mendapatkan atau menetapkan nilai dari bidang. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan vertikal dari paragraf |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau menetapkan lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau menetapkan nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Menerima pengunjung. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Menambahkan opsi baru dengan nama yang ditentukan. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Menambahkan opsi baru dengan nilai ekspor dan nama yang ditentukan. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Menghapus opsi berdasarkan namanya. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Menjalankan tindakan JavaScript yang ditentukan untuk bidang. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke aliran yang disediakan. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke file yang ditentukan. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Mengekspor konten bidang yang ditentukan ke dalam aliran JSON. Nilai bidang tombol tidak diekspor. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Menghapus bidang ini dan menempatkan nilainya langsung di halaman. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mengembalikan nama status "tercentang" sesuai dengan nama status yang ada. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Mengembalikan enumerator dari bidang yang terkandung. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Mengimpor data ke dalam bidang yang ditentukan dari aliran JSON, berdasarkan kecocokan tepat dengan nama lengkap bidang. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Mengimpor data ke dalam bidang yang ditentukan dari aliran JSON, menggunakan nama lengkap yang ditentukan dalam variabel 'fieldFullNameInJSON' untuk pencocokan. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Menghitung ulang semua bidang yang dihitung pada formulir. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Menetapkan posisi bidang. |

### Lihat Juga

* kelas [ChoiceField](../choicefield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)