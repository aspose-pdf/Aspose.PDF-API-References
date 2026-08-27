---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili Antarmuka formulir Acro."
type: docs
weight: 230
url: /id/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Mewakili Antarmuka formulir Acro.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Menginisialisasi facade. |
| [close](#close--) | Menutup semua sumber daya yang terbuka yang digunakan oleh dokumen ini. |
| [dispose](#dispose--) | Usang. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Mengekspor konten bidang-bidang pdf ke dalam aliran fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Mengekspor konten bidang-bidang pdf ke dalam aliran xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Mengekspor konten bidang-bidang pdf ke dalam aliran xml. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Mengekstrak paket data XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [fillField](#fillField-java.lang.String-boolean-) | Mengisi bidang kotak centang dengan nilai boolean. |
| [fillField](#fillField-java.lang.String-int-) | Mengisi bidang kotak radio dengan nilai indeks yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Mengisi bidang dengan nilai yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Isi bidang dengan beberapa pilihan. Catatan: hanya untuk bidang List Box AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Mengisi bidang dengan nilai yang ditentukan. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Menyediakan overload fungsi FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [flattenAllFields](#flattenAllFields--) | Meratakan semua bidang. |
| [flattenField](#flattenField-java.lang.String-) | Meratakan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Mengembalikan nilai saat ini untuk bidang opsi tombol radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. |
| [getContentDisposition](#getContentDisposition--) | Konten Getshow akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [getDestFileName](#getDestFileName--) | Usang. |
| [getDestStream](#getDestStream--) | Usang. |
| [getField](#getField-java.lang.String-) | Mendapatkan nilai bidang sesuai dengan nama bidangnya. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Mengembalikan objek FrohmFieldFacade yang berisi semua atribut tampilan. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Mengembalikan flag bidang. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Dapatkan batasan bidang teks. |
| [getFieldNames](#getFieldNames--) | Mendapatkan daftar nama bidang pada formulir. |
| [getFieldType](#getFieldType-java.lang.String-) | Mengembalikan tipe bidang. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Mendapatkan semua nama tombol kirim formulir. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Mendapatkan nama lengkap bidang sesuai dengan nama pendeknya. |
| [getImportResult](#getImportResult--) | Hasil operasi impor terakhir. |
| [getResponse](#getResponse--) | Mendapatkan atau mengatur objek Response dimana hasil operasi akan disimpan. |
| [getRichText](#getRichText-java.lang.String-) | Dapatkan nilai bidang Teks Kaya, termasuk informasi pemformatan setiap karakter. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Usang. |
| [getSrcStream](#getSrcStream--) | Mendapatkan aliran sumber. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Mengembalikan flag pengiriman tombol kirim. |
| [importFdf](#importFdf-java.io.InputStream-) | Mengimpor konten bidang dari file fdf dan menempatkannya ke PDF baru. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Mengimpor konten bidang dari file xfdf(xml) dan menempatkannya ke PDF baru. |
| [importXml](#importXml-java.io.InputStream-) | Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. |
| [importXml](#importXml-java.lang.String-) | Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Menentukan apakah bidang wajib atau tidak. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Mengganti nama bidang. |
| [save](#save--) | <p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Usang. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Usang. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Mendapatkan atau mengatur objek Response dimana hasil operasi akan disimpan. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Usang. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Mendapatkan aliran sumber. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Mengganti data XFA dengan paket data yang ditentukan. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Konstruktor FormWeb tanpa parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Menginisialisasi facade.

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang terbuka yang digunakan oleh dokumen ini.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Usang.

### exportFdf {#exportFdf-java.io.OutputStream-}
Mengekspor konten bidang-bidang pdf ke dalam aliran fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Mengekspor konten bidang-bidang pdf ke dalam aliran xml.

### exportXml {#exportXml-java.io.OutputStream-}
Mengekspor konten bidang-bidang pdf ke dalam aliran xml.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Mengekstrak paket data XFA

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
Mengisi bidang dengan nilai yang ditentukan.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Menyediakan overload fungsi FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Meratakan semua bidang.

### flattenField {#flattenField-java.lang.String-}
Meratakan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

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
public ContentDisposition getContentDisposition()
```

Konten Getshow akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

**Returns:**
Elemen ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Usang.

**Returns:**
Objek String

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Usang.

**Returns:**
objek OutputStream

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
public String [] getFieldNames()
```

Mendapatkan daftar nama bidang pada formulir.

**Returns:**
objek String[]

### getFieldType {#getFieldType-java.lang.String-}
Mengembalikan tipe bidang.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Mendapatkan semua nama tombol kirim formulir.

**Returns:**
objek String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Mendapatkan nama lengkap bidang sesuai dengan nama pendeknya.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Hasil operasi impor terakhir.

**Returns:**
FormImportResult[] array

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Mendapatkan atau mengatur objek Response dimana hasil operasi akan disimpan.

**Returns:**
Objek HttpServletResponse

### getRichText {#getRichText-java.lang.String-}
Dapatkan nilai bidang Teks Kaya, termasuk informasi pemformatan setiap karakter.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

**Returns:**
Objek SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Usang.

**Returns:**
Objek String

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
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

### importXml {#importXml-java.lang.String-}
Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru.

### isRequiredField {#isRequiredField-java.lang.String-}
Menentukan apakah bidang wajib atau tidak.

### renameField {#renameField-java.lang.String-java.lang.String-}
Mengganti nama bidang.

### save {#save--}
```
public void save()
```

<p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Usang.

### setDestStream {#setDestStream-java.io.OutputStream-}
Usang.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Mendapatkan atau mengatur objek Response dimana hasil operasi akan disimpan.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Usang.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Mendapatkan aliran sumber.

### setXfaData {#setXfaData-java.io.InputStream-}
Mengganti data XFA dengan paket data yang ditentukan.
