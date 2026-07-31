---
title: "Kelas Form"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "kelas Aspose.Pdf.Forms.Form. Kelas yang mewakili objek formulir"
type: docs
weight: 5190
url: /id/net/aspose.pdf.forms/form/
---
## Form class

Kelas yang mewakili objek formulir.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Jika diatur, semua bidang formulir akan dihitung ulang ketika ada bidang yang berubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi formulir dengan banyak bidang yang dihitung. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Jika diatur, bidang formulir yang tidak ada akan secara otomatis dibuat jika mereka ada dalam anotasi. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Memungkinkan mengatur urutan perhitungan bidang. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Mendapatkan jumlah bidang pada formulir ini. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Mendapatkan atau mengatur tampilan default formulir (objek yang menjelaskan font default, ukuran teks, dan warna untuk bidang pada formulir). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Mendapatkan sumber daya default yang ditempatkan pada formulir ini. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Jika properti ini bernilai true, maka persegi panjang batas merah tambahan akan digambar untuk kontainer elemen Xfa exclGroup yang diperlukan. Properti ini diperkenalkan karena tidak adanya analog untuk exclGroup selama konversi representasi Xfa formulir ke standar. Nilainya false secara default. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Mendapatkan daftar semua bidang pada tingkat terendah dari formulir hierarkis. |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | Mendapatkan nilai yang menunjukkan apakah dokumen berisi formulir XFA. Properti ini diperkenalkan untuk menentukan apakah [`IgnoreNeedsRendering`](./ignoreneedsrendering/) harus digunakan untuk menghapus formulir XFA dalam kasus di mana formulir XFA hadir dan [`NeedsRendering`](./needsrendering/) bernilai false. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Jika properti ini bernilai true, nilai kunci NeedsRendering akan diabaikan selama konversi formulir XFA ke formulir Standar. Nilainya false secara default. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Mengembalikan true jika objek bersifat thread-safe. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Mendapatkan bidang formulir berdasarkan nama bidang. Melempar pengecualian jika bidang tidak ditemukan. (2 indexers) |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | Mendapatkan nilai yang menunjukkan apakah dokumen memerlukan penghapusan formulir XFA dinamis. Properti ini diperkenalkan untuk menentukan apakah [`IgnoreNeedsRendering`](./ignoreneedsrendering/) harus digunakan untuk menghapus formulir XFA dalam kasus di mana formulir XFA hadir dan [`NeedsRendering`](./needsrendering/) bernilai false. |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Jika properti ini bernilai true, kamus "Perms" akan dihapus dari dokumen pdf setelah mengonversi dokumen dinamis ke standar. Kamus "Perms" dapat berisi aturan yang mengganggu penampilan pilihan bidang wajib di Adobe Acrobat Reader. Nilainya false secara default. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Jika diatur, dokumen berisi tanda tangan yang dapat menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, bukan sebagai pembaruan inkremental. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Jika diatur, dokumen berisi setidaknya satu bidang tanda tangan. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Mengembalikan objek sinkronisasi. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Mendapatkan tipe formulir. Nilai yang mungkin: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Mendapatkan data XFA dari formulir (jika ada). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Menambahkan bidang pada formulir. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Menambahkan bidang pada formulir. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Menambahkan bidang baru ke formulir; Jika bidang ini sudah ditempatkan pada formulir lain atau formulir ini, salinan bidang akan dibuat. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Menambahkan tampilan tambahan bidang ke halaman tertentu dari dokumen pada lokasi yang ditentukan. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Mengatur XFA formulir ke nilai yang ditentukan. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Menyalin bidang yang ditempatkan pada formulir ke dalam array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Menghapus bidang dari formulir. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Menghapus bidang dari formulir berdasarkan namanya. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke aliran yang disediakan. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke file yang ditentukan. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Menghapus semua bidang formulir dan menempatkan nilainya langsung pada halaman. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Mendapatkan enumerasi bidang formulir. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Mengembalikan bidang di dalam persegi panjang yang ditentukan. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Periksa apakah formulir sudah memiliki bidang yang ditentukan. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Form. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Form, dengan kemampuan untuk melihat hierarki anak bidang. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Mengimpor bidang formulir PDF dari format JSON yang disediakan dalam aliran. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Mengimpor bidang formulir PDF dari format JSON yang disediakan dalam file yang ditentukan. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Membuat anotasi bidang formulir menjadi independen. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Menghapus tampilan bidang pada indeks yang ditentukan. Jika hanya satu tampilan anak yang tersisa, metode menyematkannya ke dalam bidang. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Formulir dapat berisi informasi penandatanganan, yaitu dapat ditandatangani atau tidak ditandatangani. Dan tampilan formulir terkadang harus bergantung pada apakah formulir ditandatangani atau tidak. Properti ini memberi tahu konverter formulir (misalnya selama konversi formulir XFA ke formulir Standar) apakah formulir hasil harus dirender sebagai ditandatangani atau tidak ditandatangani. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Kelas yang menjelaskan pengaturan untuk prosedur pelurusan Formulir. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Formulir dapat berisi informasi penandatanganan dan dapat ditandatangani atau tidak ditandatangani. Terkadang tampilan formulir di penampil harus bergantung pada apakah formulir ditandatangani atau tidak. Enum ini mengenumerasi mode rendering yang mungkin selama konversi tipe formulir terkait tanda tangan. |

### Lihat Juga

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


