---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.Form. Kelas yang mewakili objek form Acro
type: docs
weight: 4290
url: /id/net/aspose.pdf.facades/form/
---
## Kelas Form

Kelas yang mewakili objek form Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Form](form/#constructor)() | Konstruktor Form tanpa parameter. |
| [Form](form/#constructor_1)(Document) | Menginisialisasi objek `Form` baru berdasarkan *dokumen*. |
| [Form](form/#constructor_4)(Stream) | Konstruktor untuk form. |
| [Form](form/#constructor_7)(string) | Konstruktor Form. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan, maka file akan disimpan dalam format PDF default tanpa konversi. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Mendapatkan daftar nama field pada form. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Mendapatkan semua nama tombol kirim form. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Hasil dari operasi impor terakhir. Array objek yang menggambarkan hasil impor untuk setiap field. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Menutup file yang dibuka tanpa perubahan. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Mengekspor konten field dari pdf ke dalam stream fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Mengekspor konten semua field dalam dokumen ke dalam stream JSON. Nilai field tombol tidak diekspor. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Mengekspor konten field dari pdf ke dalam stream xml. Nilai field tombol tidak akan diekspor. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Mengekspor konten field dari pdf ke dalam stream xml. Nilai field tombol tidak akan diekspor. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Mengekstrak paket data XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Mengisi field barcode sesuai dengan nama field yang sepenuhnya memenuhi syarat. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Mengisi field kotak centang dengan nilai boolean. Catatan: Hanya berlaku untuk Kotak Centang. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak bekerja dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya, jika field memiliki nama lengkap "Form.Subform.CheckBoxField", Anda harus menentukan nama lengkap dan bukan "CheckBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Mengisi field radio box dengan nilai indeks yang valid sesuai dengan nama field yang sepenuhnya memenuhi syarat. Sebelum mengisi field, hanya nama field yang harus diketahui. Sementara nilai dapat ditentukan berdasarkan indeksnya. Catatan: Hanya berlaku untuk Radio Box, Combo Box, dan List Box fields. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak bekerja dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya, jika field memiliki nama lengkap "Form.Subform.ListBoxField", Anda harus menentukan nama lengkap dan bukan "ListBoxField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Mengisi field dengan nilai yang valid sesuai dengan nama field yang sepenuhnya memenuhi syarat. Sebelum mengisi field, setiap nama field dan nilai valid yang sesuai harus diketahui. Baik nama field maupun nilai bersifat case sensitive. Harap dicatat bahwa Aspose.Pdf.Facades hanya mendukung nama field lengkap dan tidak bekerja dengan nama field parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya, jika field memiliki nama lengkap "Form.Subform.TextField", Anda harus menentukan nama lengkap dan bukan "TextField". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama field yang ada dan mencari field yang diperlukan berdasarkan nama parsialnya. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Mengisi field dengan beberapa pilihan. Catatan: hanya untuk AcroForm List Box Field. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Mengisi field dengan nilai yang ditentukan. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Mengisi field kotak teks dengan nilai teks dan menyimpan dokumen. Relevan untuk dokumen yang ditandatangani. Catatan: Hanya berlaku untuk Kotak Teks. Baik nama field maupun nilai bersifat case sensitive. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Meng-overload fungsi FillImageField. Input adalah stream gambar. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Menempelkan gambar ke field tombol yang ada sebagai tampilannya sesuai dengan nama field yang sepenuhnya memenuhi syarat. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Meratakan semua field. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Meratakan field yang ditentukan dengan nama field yang sepenuhnya memenuhi syarat. Field lainnya akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua field akan tetap tidak dapat diubah. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Mengembalikan nilai saat ini untuk field opsi tombol radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Mendapatkan field opsi tombol radio dan nilai terkait berdasarkan nama field. Metode ini memiliki arti untuk grup tombol radio. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Mendapatkan nilai field sesuai dengan nama fieldnya. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Mengembalikan objek FrofmFieldFacade yang berisi semua atribut tampilan. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Mengembalikan bendera dari field. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Mendapatkan batasan dari field teks. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Mengembalikan tipe field. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Mendapatkan nama field lengkap sesuai dengan nama field pendeknya. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Mendapatkan nilai field Rich Text, termasuk informasi pemformatan dari setiap karakter. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Mengembalikan bendera pengiriman tombol kirim |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Mengimpor konten field dari file fdf dan menempatkannya ke dalam pdf baru. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Mengimpor semua data field dari stream JSON ke dalam field dokumen, mencocokkan field berdasarkan nama lengkapnya. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Mengimpor konten field dari file xfdf(xml) dan menempatkannya ke dalam pdf baru. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Mengimpor konten field dari file xml dan menempatkannya ke dalam pdf baru. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Mengimpor konten field dari file xml dan menempatkannya ke dalam pdf baru. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Menentukan apakah field diperlukan atau tidak. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Mengganti nama field. Baik field AcroForm maupun field XFA diperbolehkan. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Menyimpan dokumen ke dalam stream yang ditentukan. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Menyimpan dokumen ke dalam file yang ditentukan. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Mengganti data XFA dengan paket data yang ditentukan. Paket data dapat diekstrak menggunakan ExtractXfaData. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Kelas yang menggambarkan hasil jika field diimpor. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status field yang diimpor |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)