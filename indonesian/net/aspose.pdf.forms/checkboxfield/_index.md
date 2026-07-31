---
title: "Kelas CheckboxField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Forms.CheckboxField. Kelas yang mewakili bidang kotak centang"
type: docs
weight: 5100
url: /id/net/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class

Kelas yang mewakili bidang kotak centang

```csharp
public class CheckboxField : Field
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CheckboxField](checkboxfield/#constructor_1)(Document) | Konstruktor untuk digunakan dengan Generator. |
| [CheckboxField](checkboxfield/#constructor_2)(Document, Rectangle) | Konstruktor untuk kelas CheckboxField. |
| [CheckboxField](checkboxfield/#constructor_3)(Page, Rectangle) | Konstruktor untuk kelas CheckboxField. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Mendapatkan aksi annotation. (2 properti) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate/) { get; set; } | Mendapatkan atau mengatur status tampilan annotation saat ini. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates/) { get; } | Mengembalikan daftar status yang diizinkan. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Mendapatkan atau mengatur nama alternatif dari field (Nama field alternatif yang harus digunakan menggantikan nama field sebenarnya di mana pun field harus diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip field di Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Mendapatkan atau mengatur indeks anotation ini pada page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Mendapatkan tipe annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan dari annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau mengatur karakteristik border annotation. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik annotation. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked/) { get; set; } | Mendapatkan atau mengatur status kotak centang. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau mengatur warna annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau mengatur teks annotation. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Mendapatkan jumlah subfields dalam field ini. (Sebagai contoh jumlah item dalam field tombol radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Mendapatkan atau mengatur penampilan default dari field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Mendapatkan atau mengatur flag dapat diekspor dari field. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue/) { get; set; } | Mendapatkan atau mengatur nilai ekspor bidang CheckBox. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau mengatur tinggi annotation. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Mode penyorotan annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah field ini adalah field non-terminal, yaitu grup field. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Properti untuk dukungan Generator. Digunakan ketika field ditambahkan ke header atau footer. Jika true, field ini akan dibuat satu kali dan penampilannya akan terlihat pada semua page Document. Jika false, field terpisah akan dibuat untuk setiap page Document. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Mengembalikan true jika dictionary disinkronkan. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Mendapatkan subfield yang terdapat dalam field ini berdasarkan nama subfield. (2 indexer) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Mendapatkan atau mengatur nama pemetaan field yang akan digunakan saat mengekspor data field formulir interaktif dari Document. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau mengatur tanggal dan waktu ketika anotasi baru-baru ini dimodifikasi. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau mengatur nama anotasi pada halaman. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Tindakan yang akan dilakukan ketika anotasi diaktifkan. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi bidang ini. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Mendapatkan induk anotasi. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Mendapatkan atau mengatur nama parsial bidang. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Mendapatkan atau mengatur status hanya-baca bidang. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang bidang. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Mendapatkan atau mengatur status wajib bidang. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus tampilan anotasi. |
| [Style](../../aspose.pdf.forms/checkboxfield/style/) { get; set; } | Mendapatkan atau mengatur gaya kotak centang. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objek sinkronisasi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Mendapatkan atau mengatur urutan tab bidang. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value/) { get; set; } | Mendapatkan atau mengatur nilai bidang kotak centang. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau mengatur lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Menerima pengunjung. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption)(string) | Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dicentang pada satu waktu. Kotak centang baru ditambahkan ke bagian bawah grup. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_1)(string, Rectangle) | Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dicentang pada satu waktu. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_2)(string, int, Rectangle) | Menambahkan kotak centang baru ke dalam grup kotak centang, di mana paling banyak satu kotak centang dapat dicentang pada satu waktu. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone/)() | Klon kotak centang. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Menjalankan tindakan JavaScript yang ditentukan untuk bidang. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke aliran yang disediakan. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke file yang ditentukan. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Mengekspor konten bidang yang ditentukan ke aliran JSON. Nilai bidang tombol tidak diekspor. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Menghapus bidang ini dan menempatkan nilainya langsung pada halaman. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mengembalikan nama status "checked" sesuai dengan nama status yang ada. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Mengembalikan enumerator dari bidang-bidang yang terkandung. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Mengimpor data ke bidang-bidang yang ditentukan dari aliran JSON, berdasarkan kecocokan tepat nama lengkap bidang. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Mengimpor data ke bidang yang ditentukan dari aliran JSON, menggunakan nama lengkap yang ditentukan dalam variabel 'fieldFullNameInJSON' untuk pencocokan. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Menghitung ulang semua bidang yang dihitung pada formulir. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Atur posisi bidang. |

## Contoh

Contoh ini menunjukkan cara membuat bidang kotak centang multi-nilai.

```csharp
using (var document = new Document())
{
var page = document.Pages.Add();

var checkbox = new CheckboxField(page, new Rectangle(50, 50, 70, 70));

// Atur nilai opsi grup kotak centang pertama
checkbox.ExportValue = "option 1";

// Tambahkan opsi baru tepat di bawah yang ada
checkbox.AddOption("option 2");

// Tambahkan opsi baru pada persegi panjang yang diberikan
checkbox.AddOption("option 3", new Rectangle(100, 100, 120, 120));

document.Form.Add(checkbox);

// Pilih kotak centang yang ditambahkan
checkbox.Value = "option 2";
document.Save("checkbox_group.pdf");
}
```

### Lihat Juga

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


