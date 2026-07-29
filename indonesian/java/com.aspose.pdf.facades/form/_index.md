---
title: "Formulir"
linktitle: "Formulir"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili objek formulir Acro."
type: docs
weight: 170
url: /id/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Kelas yang mewakili objek formulir Acro.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Form](#Form--) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Menginisialisasi facade. |
| [close](#close--) | Menutup file yang dibuka tanpa perubahan apa pun. |
| [dispose](#dispose--) | Menutup semua sumber daya yang dibuka. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Mengekspor konten bidang PDF ke aliran fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Mengekspor konten bidang PDF ke aliran xml. Nilai bidang tombol tidak akan diekspor. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Mengekspor konten bidang PDF ke aliran xml. Nilai bidang tombol tidak akan diekspor. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Mengekstrak paket data XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Mengisi bidang kotak centang dengan nilai boolean. Catatan: Hanya dapat diterapkan pada Check Box. Harap perhatikan bahwa Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap \"Form.Subform.CheckBoxField\" Anda harus menentukan nama lengkap dan bukan \"CheckBoxField\". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Mengisi bidang kotak radio dengan nilai indeks yang valid sesuai nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, hanya nama bidang yang harus diketahui. Nilai dapat ditentukan dengan indeksnya. Catatan: Hanya berlaku untuk bidang Radio Box, Combo Box, dan List Box. Harap dicatat bahwa Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap \"Form.Subform.ListBoxField\" Anda harus menentukan nama lengkap dan bukan \"ListBoxField\". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Mengisi bidang dengan nilai yang valid sesuai nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, nama setiap bidang dan nilai valid yang sesuai harus diketahui. Baik nama bidang maupun nilai bersifat case sensitive. Harap dicatat bahwa Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap \"Form.Subform.TextField\" Anda harus menentukan nama lengkap dan bukan \"TextField\". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Mengisi sebuah bidang dengan beberapa pilihan. Catatan: hanya untuk bidang List Box AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Mengisi bidang dengan nilai yang ditentukan. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Overloads fungsi FillImageField. Inputnya adalah aliran gambar. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai nama bidang yang sepenuhnya memenuhi syarat. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Meratakan semua bidang. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Meratakan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat. Semua bidang lain akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua bidang akan tetap tidak dapat diubah. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Mengembalikan nilai saat ini untuk bidang opsi tombol radio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini berguna untuk grup tombol radio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini memiliki arti untuk grup tombol radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan atau mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [getDestFileName](#getDestFileName--) | Mendapatkan nama file tujuan. |
| [getDestStream](#getDestStream--) | Mendapatkan atau mengatur aliran tujuan. |
| [getField](#getField-java.lang.String-) | <p> Mendapatkan nilai bidang sesuai dengan nama bidangnya. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Mengembalikan objek FormFieldFacade yang berisi semua atribut tampilan. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Mengembalikan flag bidang. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Dapatkan batasan bidang teks. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Mendapatkan daftar nama bidang pada formulir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Mengembalikan tipe bidang. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Mendapatkan semua nama tombol kirim formulir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Mendapatkan nama lengkap bidang sesuai dengan nama pendek bidang. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Hasil dari operasi impor terakhir. Array objek yang menjelaskan hasil impor untuk setiap bidang. |
| [getRichText](#getRichText-java.lang.String-) | <p> Dapatkan nilai bidang Rich Text, termasuk informasi pemformatan setiap karakter. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Mendapatkan nama file sumber. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | Mendapatkan aliran sumber. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Mengimpor konten bidang dari file fdf dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Mengimpor konten bidang dari file xfdf(xml) dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. |
| [importXml](#importXml-java.lang.String-) | <p> Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Menentukan apakah bidang wajib atau tidak. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Mengganti nama sebuah bidang. Baik bidang AcroForm maupun XFA diperbolehkan. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre> |
| [save](#save--) | <p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Mengatur nama file tujuan. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Mendapatkan aliran tujuan. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Mengatur nama file sumber. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Mendapatkan aliran sumber. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Mengganti data XFA dengan paket data yang ditentukan. Paket data dapat diekstrak menggunakan ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Konstruktor Form tanpa parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Menginisialisasi facade.

### close {#close--}
```
public void close()
```

Menutup file yang dibuka tanpa perubahan apa pun.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Menutup semua sumber daya yang dibuka. Metode ini sudah usang, gunakan close() sebagai gantinya.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Mengekspor konten bidang PDF ke aliran fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Mengekspor konten bidang PDF ke aliran xml. Nilai bidang tombol tidak akan diekspor. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Mengekspor konten bidang PDF ke aliran xml. Nilai bidang tombol tidak akan diekspor. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Mengekstrak paket data XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Mengisi bidang kotak centang dengan nilai boolean. Catatan: Hanya dapat diterapkan pada Check Box. Harap perhatikan bahwa Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap \"Form.Subform.CheckBoxField\" Anda harus menentukan nama lengkap dan bukan \"CheckBoxField\". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Mengisi bidang kotak radio dengan nilai indeks yang valid sesuai nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, hanya nama bidang yang harus diketahui. Nilai dapat ditentukan dengan indeksnya. Catatan: Hanya berlaku untuk bidang Radio Box, Combo Box, dan List Box. Harap dicatat bahwa Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap \"Form.Subform.ListBoxField\" Anda harus menentukan nama lengkap dan bukan \"ListBoxField\". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Mengisi bidang dengan nilai yang valid sesuai nama bidang yang sepenuhnya memenuhi syarat. Sebelum mengisi bidang, nama setiap bidang dan nilai valid yang sesuai harus diketahui. Baik nama bidang maupun nilai bersifat case sensitive. Harap dicatat bahwa Facades hanya mendukung nama bidang lengkap dan tidak berfungsi dengan nama bidang parsial, berbeda dengan Aspose.Pdf.Kit; Misalnya jika bidang memiliki nama lengkap \"Form.Subform.TextField\" Anda harus menentukan nama lengkap dan bukan \"TextField\". Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Mengisi sebuah bidang dengan beberapa pilihan. Catatan: hanya untuk bidang List Box AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Mengisi bidang dengan nilai yang ditentukan.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Overloads fungsi FillImageField. Inputnya adalah aliran gambar. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai nama bidang yang sepenuhnya memenuhi syarat. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Meratakan semua bidang. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Meratakan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat. Semua bidang lain akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua bidang akan tetap tidak dapat diubah. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

**Returns:**
objek string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Mengembalikan nilai saat ini untuk bidang opsi tombol radio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini berguna untuk grup tombol radio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini memiliki arti untuk grup tombol radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Mendapatkan atau mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline.

**Returns:**
Elemen ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Mendapatkan nama file tujuan.

**Returns:**
objek string

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Mendapatkan atau mengatur aliran tujuan.

**Returns:**
objek OutputStream

### getField {#getField-java.lang.String-}
<p> Mendapatkan nilai bidang sesuai dengan nama bidangnya. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Mengembalikan objek FormFieldFacade yang berisi semua atribut tampilan. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Mengembalikan flag bidang. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Dapatkan batasan bidang teks. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Mendapatkan daftar nama bidang pada formulir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
objek String[]

### getFieldType {#getFieldType-java.lang.String-}
<p> Mengembalikan tipe bidang. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Mendapatkan semua nama tombol kirim formulir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
objek String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Mendapatkan nama lengkap bidang sesuai dengan nama pendek bidang. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Hasil dari operasi impor terakhir. Array objek yang menjelaskan hasil impor untuk setiap bidang.

**Returns:**
FormImportResult[] array

### getRichText {#getRichText-java.lang.String-}
<p> Dapatkan nilai bidang Rich Text, termasuk informasi pemformatan setiap karakter. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions.

**Returns:**
Objek SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Mendapatkan nama file sumber. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
objek string

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Mendapatkan aliran sumber.

**Returns:**
Objek InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Mengembalikan flag pengiriman tombol submit </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Mengimpor konten bidang dari file fdf dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Mengimpor konten bidang dari file xfdf(xml) dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru.

### importXml {#importXml-java.lang.String-}
<p> Mengimpor konten bidang dari file xml dan menaruhnya ke PDF baru. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Menentukan apakah bidang wajib atau tidak.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Mengganti nama sebuah bidang. Baik bidang AcroForm maupun XFA diperbolehkan. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre>

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
Mengatur cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Mengatur nama file tujuan. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Mendapatkan aliran tujuan. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Mengatur nama file sumber.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Mendapatkan aliran sumber. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Mengganti data XFA dengan paket data yang ditentukan. Paket data dapat diekstrak menggunakan ExtractXfaData.
