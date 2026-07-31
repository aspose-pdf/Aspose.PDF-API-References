---
title: "Kelas FormEditor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.FormEditor. Kelas untuk mengedit formulir menambah/menghapus bidang, dll"
type: docs
weight: 4450
url: /id/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Kelas untuk mengedit formulir (menambah/menghapus bidang, dll).

```csharp
public sealed class FormEditor : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Konstruktor untuk FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Menginisialisasi objek `FormEditor` baru berdasarkan *document*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan, maka file akan disimpan dalam format PDF default tanpa konversi. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Mengatur opsi untuk combo box dengan nilai ekspor. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Mengatur atribut visual bidang. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Mengatur item yang akan ditambahkan ke list box atau combo box yang baru dibuat. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Anggota untuk mencatat jarak antara dua tombol radio yang berdekatan dalam piksel, defaultnya adalah 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Bendera untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Atur bendera pengiriman tombol submit |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Tambahkan bidang dengan tipe yang ditentukan ke formulir. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Tambahkan bidang dengan tipe yang ditentukan ke formulir. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Tambahkan JavaScript untuk bidang PushButton. Jika acara lama ada, acara baru akan ditambahkan setelahnya. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Menambahkan item baru ke list box. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Tambahkan item baru dengan nilai Export ke bidang list box yang ada, hanya untuk bidang combo box AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Tambahkan tombol submit pada formulir. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Menutup facade. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Menyalin field yang ada ke posisi yang sama pada nomor halaman yang ditentukan. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali field yang baru disalin. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Menyalin field yang ada ke posisi baru yang ditentukan oleh nomor halaman dan ordinat. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali field yang baru disalin. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat asli. Catatan: Hanya untuk field AcroForm (tidak termasuk kotak radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat asli. Catatan: Hanya untuk field AcroForm (tidak termasuk kotak radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat yang ditentukan. Catatan: Hanya untuk field AcroForm (tidak termasuk kotak radio). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Mengubah atribut visual semua field dalam dokumen PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Mengubah atribut visual semua field dengan tipe field yang ditentukan. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Mengubah atribut visual field yang ditentukan. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Menghapus item dari field daftar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Mendapatkan flag field. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Mengatur posisi baru field. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Menghapus field dari formulir. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Menghapus aksi submit field. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Mengubah nama field. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Mengatur ulang semua atribut visual ke nilai kosong. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Mengatur ulang semua atribut visual dari facade internal ke nilai kosong. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Mengatur gaya perataan field teks. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Mengatur gaya perataan vertikal field teks. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Mengatur flag field. |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Mengatur atribut field. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Mengatur jumlah comb untuk field teks satu baris reguler (field secara otomatis dibagi menjadi sebanyak posisi yang berjarak sama, atau comb, sesuai nilai parameter combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Mengatur jumlah karakter maksimum dari bidang teks. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Atur JavaScript untuk bidang PushButton. Jika JavaScript lama ada, itu akan diganti dengan yang baru. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Atur flag submit pada tombol submit. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Mengatur URL tombol. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Ubah bidang teks satu baris menjadi beberapa baris. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


