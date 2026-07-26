---
title: "IForm"
linktitle: "IForm"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili objek formulir Acro."
type: docs
weight: 250
url: /id/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Kelas yang mewakili objek formulir Acro.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [close](#close--) | Menutup file yang dibuka tanpa perubahan apa pun. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Mengekspor konten bidang-bidang pdf ke dalam aliran fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Mengekspor konten bidang-bidang pdf ke dalam aliran xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Mengekspor konten bidang-bidang pdf ke dalam aliran xml. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [fillField](#fillField-java.lang.String-boolean-) | Mengisi bidang kotak centang dengan nilai boolean. |
| [fillField](#fillField-java.lang.String-int-) | Mengisi bidang kotak radio dengan nilai indeks yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Mengisi bidang dengan nilai yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Isi bidang dengan beberapa pilihan. Catatan: hanya untuk bidang List Box AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Menyediakan overload fungsi FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [flattenAllFields](#flattenAllFields--) | Meratakan semua bidang. |
| [flattenField](#flattenField-java.lang.String-) | Meratakan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan atau mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Mengembalikan nilai saat ini untuk bidang opsi tombol radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan atau mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [getDestFileName](#getDestFileName--) | Mendapatkan nama file tujuan. |
| [getDestStream](#getDestStream--) | Mendapatkan aliran tujuan. |
| [getDocument](#getDocument--) | Mendapatkan Form dokumen yang sedang dikerjakan. |
| [getField](#getField-java.lang.String-) | Mendapatkan nilai bidang sesuai dengan nama bidangnya. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Mengembalikan objek FrohmFieldFacade yang berisi semua atribut tampilan. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Mengembalikan flag bidang. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Dapatkan batasan bidang teks. |
| [getFieldNames](#getFieldNames--) | Mendapatkan daftar nama bidang pada formulir. |
| [getFieldType](#getFieldType-java.lang.String-) | Mengembalikan tipe bidang. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Mendapatkan semua nama tombol kirim formulir. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Mendapatkan nama lengkap bidang sesuai dengan nama pendeknya. |
| [getRichText](#getRichText-java.lang.String-) | Dapatkan nilai bidang Teks Kaya, termasuk informasi pemformatan setiap karakter. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Mendapatkan nama file sumber. |
| [getSrcStream](#getSrcStream--) | Mendapatkan aliran sumber. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Mengembalikan flag pengiriman tombol kirim. |
| [importFdf](#importFdf-java.io.InputStream-) | Mengimpor konten bidang dari file fdf dan menempatkannya ke PDF baru. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Mengimpor konten bidang dari file xfdf(xml) dan menempatkannya ke PDF baru. |
| [importXml](#importXml-java.io.InputStream-) | Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Mengganti nama bidang. |
| [save](#save--) | Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Mengatur nama file tujuan. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Mendapatkan aliran tujuan. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Mengatur nama file sumber. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Mendapatkan aliran sumber. |

### close {#close--}
```
void close()
```

Menutup file yang dibuka tanpa perubahan apa pun.

### exportFdf {#exportFdf-java.io.OutputStream-}
Mengekspor konten bidang-bidang pdf ke dalam aliran fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Mengekspor konten bidang-bidang pdf ke dalam aliran xml.

### exportXml {#exportXml-java.io.OutputStream-}
Mengekspor konten bidang-bidang pdf ke dalam aliran xml.

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

### fillField {#fillField-java.lang.String-boolean-}
Mengisi bidang kotak centang dengan nilai boolean.

### fillField {#fillField-java.lang.String-int-}
Mengisi bidang kotak radio dengan nilai indeks yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

### fillField {#fillField-java.lang.String-java.lang.String-}
Mengisi bidang dengan nilai yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Isi bidang dengan beberapa pilihan. Catatan: hanya untuk bidang List Box AcroForm.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Menyediakan overload fungsi FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Meratakan semua bidang.

### flattenField {#flattenField-java.lang.String-}
Meratakan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Mendapatkan atau mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

**Returns:**
objek string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Mengembalikan nilai saat ini untuk bidang opsi tombol radio.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang.

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Mendapatkan atau mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

**Returns:**
Elemen ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Mendapatkan nama file tujuan.

**Returns:**
Objek String

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Mendapatkan aliran tujuan.

**Returns:**
objek OutputStream

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Mendapatkan Form dokumen yang sedang dikerjakan.

**Returns:**
objek IDocument

### getField {#getField-java.lang.String-}
Mendapatkan nilai bidang sesuai dengan nama bidangnya.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Mengembalikan objek FrohmFieldFacade yang berisi semua atribut tampilan.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Mengembalikan flag bidang.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Dapatkan batasan bidang teks.

### getFieldNames {#getFieldNames--}
```
String [] getFieldNames()
```

Mendapatkan daftar nama bidang pada formulir.

**Returns:**
objek String[]

### getFieldType {#getFieldType-java.lang.String-}
Mengembalikan tipe bidang.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Mendapatkan semua nama tombol kirim formulir.

**Returns:**
objek String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Mendapatkan nama lengkap bidang sesuai dengan nama pendeknya.

### getRichText {#getRichText-java.lang.String-}
Dapatkan nilai bidang Teks Kaya, termasuk informasi pemformatan setiap karakter.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

**Returns:**
Objek SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Mendapatkan nama file sumber.

**Returns:**
Objek String

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Mendapatkan aliran sumber.

**Returns:**
Objek InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Mengembalikan flag pengiriman tombol kirim.

### importFdf {#importFdf-java.io.InputStream-}
Mengimpor konten bidang dari file fdf dan menempatkannya ke PDF baru.

### importXfdf {#importXfdf-java.io.InputStream-}
Mengimpor konten bidang dari file xfdf(xml) dan menempatkannya ke PDF baru.

### importXml {#importXml-java.io.InputStream-}
Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru.

### importXml {#importXml-java.io.InputStream-boolean-}
Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru.

### renameField {#renameField-java.lang.String-java.lang.String-}
Mengganti nama bidang.

### save {#save--}
```
void save()
```

Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Mengatur nama file tujuan.

### setDestStream {#setDestStream-java.io.OutputStream-}
Mendapatkan aliran tujuan.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Mengatur nama file sumber.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Mendapatkan aliran sumber.
