---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form class. Kelas yang merepresentasikan objek form
type: docs
weight: 5070
url: /id/net/aspose.pdf.forms/form/
---
## Kelas Form

Kelas yang merepresentasikan objek form.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Properti

| Name | Description |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Jika diatur, semua field form akan dihitung ulang ketika ada field yang diubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi form dengan sejumlah besar field yang dihitung. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Jika diatur, field form yang tidak ada akan dibuat secara otomatis jika terdapat dalam annotations. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Memungkinkan pengaturan urutan perhitungan field. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Mengambil jumlah field pada form ini. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Mengambil atau mengatur tampilan default form (objek yang menggambarkan font, ukuran teks, dan warna default untuk field pada form). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Mengambil sumber daya default yang terdapat pada form ini. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Jika properti ini bernilai true, maka rectangle batas berwarna merah tambahan akan digambar untuk container elemen exclGroup Xfa yang diperlukan. Properti ini diperkenalkan karena tidak adanya analog untuk exclGroup selama konversi representasi Xfa form ke Standard. Nilai defaultnya adalah false. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Mengambil daftar semua field di tingkat terendah dari form hierarkis. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Jika properti ini bernilai true, maka nilai kunci NeedsRendering akan diabaikan selama konversi form XFA ke form Standard. Nilai defaultnya adalah false. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Mengembalikan true jika objek aman untuk multi-threading. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Mengambil field form berdasarkan nama field. Melempar exception jika field tidak ditemukan. (2 indexer) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Jika properti ini bernilai true, maka kamus "Perms" akan dihapus dari dokumen pdf setelah konversi dokumen dinamis ke Standard. Kamus "Perms" dapat mengandung aturan yang mengganggu tampilan pilihan field wajib di Adobe Acrobat Reader. Nilai defaultnya adalah false. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Jika diatur, dokumen mengandung tanda tangan yang mungkin menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, bukan melalui pembaruan incremental. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Jika diatur, dokumen mengandung setidaknya satu field tanda tangan. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Mengembalikan objek sinkronisasi. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Mengambil jenis form. Nilai yang mungkin adalah: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Mengambil data XFA dari form (jika ada). |

## Metode

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Menambahkan field ke form. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Menambahkan field ke form. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Menambahkan field baru ke form; Jika field ini sudah ada di form lain atau form ini, salinan field akan dibuat. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Menambahkan tampilan tambahan untuk field ke halaman yang ditentukan dari dokumen di lokasi yang ditentukan. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Mengatur XFA form ke nilai yang ditentukan. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Menyalin field yang ada pada form ke dalam array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Menghapus field dari form. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Menghapus field dari form berdasarkan namanya. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Mengekspor field-field form PDF ke format JSON dan menulis hasilnya ke stream yang disediakan. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Mengekspor field-field form PDF ke format JSON dan menulis hasilnya ke file yang ditentukan. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Menghapus semua field form dan menempatkan nilainya langsung pada halaman. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Mengambil enumerasi field form. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Mengembalikan field yang berada di dalam rectangle yang ditentukan. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Memeriksa apakah form sudah memiliki field yang ditentukan. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Menentukan apakah field dengan nama yang ditentukan sudah ditambahkan ke Form. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Menentukan apakah field dengan nama yang ditentukan sudah ditambahkan ke Form, dengan kemampuan untuk mencari dalam hierarki anak field. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Mengimpor field-field form PDF dari format JSON yang disediakan dalam stream. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Mengimpor field-field form PDF dari format JSON yang disediakan dalam file yang ditentukan. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Membuat anotasi field form menjadi independen. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Menghapus tampilan field pada indeks yang ditentukan. Jika hanya tersisa satu tampilan anak, metode ini akan menyematkannya ke dalam field. |

## Field

| Name | Description |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Form dapat mengandung informasi tanda tangan, yaitu dapat ditandatangani atau tidak ditandatangani. Dan tampilan form terkadang harus bergantung pada apakah form ditandatangani atau tidak. Properti ini memberitahu converter form (misalnya, selama konversi form XFA ke form Standard) apakah hasil form harus ditampilkan sebagai ditandatangani atau tidak. |

## Anggota Lain

| Name | Description |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Kelas yang menggambarkan pengaturan untuk prosedur flattening form. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Form dapat mengandung informasi tanda tangan dan dapat ditandatangani atau tidak ditandatangani. Terkadang tampilan form di viewer harus bergantung pada apakah form ditandatangani atau tidak. Enum ini mendaftar mode rendering yang mungkin selama konversi tipe form terkait tanda tangan. |

### Lihat Juga

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)