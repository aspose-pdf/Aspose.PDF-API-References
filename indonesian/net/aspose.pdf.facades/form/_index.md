---
title: "Kelas Form"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.Form. Kelas yang mewakili objek formulir Acro"
type: docs
weight: 4410
url: /id/net/aspose.pdf.facades/form/
---
## Form class

Kelas yang mewakili objek formulir Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Form](form/#constructor)() | Konstruktor Form tanpa parameter. |
| [Form](form/#constructor_1)(Document) | Menginisialisasi objek `Form` baru berdasarkan *dokumen*. |
| [Form](form/#constructor_4)(Stream) | Konstruktor untuk formulir. |
| [Form](form/#constructor_7)(string) | Konstruktor Form. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan, maka file akan disimpan dalam format PDF default tanpa konversi. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Mendapatkan daftar nama bidang pada formulir. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Mendapatkan semua nama tombol kirim formulir. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Hasil operasi impor terakhir. Array objek yang menjelaskan hasil impor untuk setiap bidang. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Menutup file yang dibuka tanpa melakukan perubahan apa pun. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Mengekspor konten bidang pdf ke dalam aliran fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Mengekspor isi semua bidang dalam dokumen ke aliran JSON. Nilai bidang tombol tidak diekspor. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Mengekspor konten bidang pdf ke dalam aliran xml. Nilai bidang tombol tidak akan diekspor. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Mengekspor konten bidang pdf ke dalam aliran xml. Nilai bidang tombol tidak akan diekspor. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Mengekstrak paket data XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Isi bidang kotak centang dengan nilai boolean. Catatan: Hanya berlaku untuk Check Box. Harap perhatikan bahwa Aspose.Pdf.Facades mendukung hanya nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap "Form.Subform.CheckBoxField" Anda harus menentukan nama lengkap dan bukan "CheckBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Isi bidang radio box dengan nilai indeks yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, hanya nama bidang yang harus diketahui. Nilai dapat ditentukan dengan indeksnya. Catatan: Hanya berlaku untuk bidang Radio Box, Combo Box, dan List Box. Harap perhatikan bahwa Aspose.Pdf.Facades mendukung hanya nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap "Form.Subform.ListBoxField" Anda harus menentukan nama lengkap dan bukan "ListBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Isi bidang dengan nilai yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, setiap nama bidang dan nilai valid yang sesuai harus diketahui. Baik nama bidang maupun nilai bersifat sensitif huruf. Harap perhatikan bahwa Aspose.Pdf.Facades mendukung hanya nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap "Form.Subform.TextField" Anda harus menentukan nama lengkap dan bukan "TextField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Isi bidang dengan beberapa pilihan. Catatan: hanya untuk AcroForm List Box Field. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Isi bidang dengan nilai yang ditentukan. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Isi bidang kotak teks dengan nilai teks dan simpan dokumen. Relevan untuk dokumen yang ditandatangani. Catatan: Hanya berlaku untuk Text Box. Baik nama bidang maupun nilai bersifat sensitif huruf. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Membebani fungsi FillImageField. Inputnya adalah aliran gambar. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Menempelkan gambar ke bidang tombol yang ada sebagai tampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Menyatukan semua bidang. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Menyatukan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat. Semua bidang lain akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua bidang akan tetap tidak dapat diubah. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Mengembalikan nilai saat ini untuk bidang opsi tombol radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini berguna untuk grup tombol radio. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Mendapatkan nilai bidang berdasarkan nama bidangnya. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Mengembalikan objek FrohmFieldFacade yang berisi semua atribut tampilan. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Mengembalikan flag bidang. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Dapatkan batasan bidang teks. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Mengembalikan tipe bidang. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Mendapatkan nama bidang lengkap berdasarkan nama bidang pendeknya. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Dapatkan nilai bidang Rich Text, termasuk informasi pemformatan setiap karakter. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Mengembalikan flag pengiriman tombol submit |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Mengimpor konten bidang dari file fdf dan menaruhnya ke dalam pdf baru. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Mengimpor semua data bidang dari aliran JSON ke dalam bidang dokumen, mencocokkan bidang berdasarkan nama lengkapnya. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Mengimpor konten bidang dari file xfdf(xml) dan menaruhnya ke dalam pdf baru. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Mengimpor konten bidang dari file xml dan menaruhnya ke dalam pdf baru. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Mengimpor konten bidang dari file xml dan menaruhnya ke dalam pdf baru. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Menentukan apakah bidang wajib atau tidak. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Mengganti nama sebuah bidang. Baik bidang AcroForm maupun XFA diperbolehkan. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Menyimpan dokumen ke dalam stream yang ditentukan. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Menyimpan dokumen ke dalam file yang ditentukan. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Mengganti data XFA dengan paket data yang ditentukan. Paket data dapat diekstrak menggunakan ExtractXfaData. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Kelas yang menjelaskan hasil impor bidang. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status bidang yang diimpor |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


