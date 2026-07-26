---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk mengedit formulir (menambah/menghapus bidang, dll)."
type: docs
weight: 200
url: /id/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Kelas untuk mengedit formulir (menambah/menghapus bidang, dll).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Tambahkan bidang dengan tipe yang ditentukan ke formulir. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Tambahkan bidang dengan tipe yang ditentukan ke formulir. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Tambahkan JavaScript untuk bidang PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Menambahkan item baru ke kotak daftar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Tambahkan item baru dengan nilai Export ke bidang kotak daftar yang ada, hanya untuk bidang combo box AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Tambahkan tombol submit pada formulir. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre> |
| [close](#close--) | Tutup instance objek |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Menyalin bidang yang ada ke posisi yang sama pada nomor halaman yang ditentukan. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali bidang yang baru disalin. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Menyalin bidang yang ada ke posisi baru yang ditentukan oleh nomor halaman dan koordinat. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali bidang yang baru disalin. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat asli. Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan koordinat asli. Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat yang ditentukan. Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio). |
| [decorateField](#decorateField--) | <p> Mengubah atribut visual semua bidang dalam dokumen PDF. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // menghias semua bidang. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Mengubah atribut visual semua bidang dalam dokumen PDF. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // menghias semua bidang. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Mengubah atribut visual semua bidang dalam dokumen PDF. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // menghias semua bidang. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Hapus item dari bidang daftar. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre> |
| [dispose](#dispose--) | Tutup instance objek Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [getDestFileName](#getDestFileName--) | Mendapatkan nama file tujuan. |
| [getDestStream](#getDestStream--) | <p> Mendapatkan aliran tujuan. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [getDocument](#getDocument--) | Mendapatkan dokumen {@code FormEditor} yang sedang diproses. |
| [getExportItems](#getExportItems--) | <p> Mendapatkan opsi untuk combo box dengan nilai ekspor. </p> <hr> |
| [getFacade](#getFacade--) | Mendapatkan atribut visual dari bidang. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Dapatkan flag bidang. |
| [getItems](#getItems--) | Dapatkan Item yang akan ditambahkan ke list box atau combo box yang baru dibuat. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Dapatkan anggota untuk mencatat jarak antara dua tombol radio berdekatan dalam piksel, defaultnya 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Dapatkan flag untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Mendapatkan nama file sumber. |
| [getSrcStream](#getSrcStream--) | Mendapatkan aliran sumber. |
| [getSubmitFlag](#getSubmitFlag--) | Dapatkan flag pengiriman tombol submit |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Atur posisi baru bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Hapus bidang dari formulir. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Hapus aksi submit dari bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Ubah nama bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.renameField("textField", "textField_Renamed"); </pre> |
| [resetFacade](#resetFacade--) | Setel ulang semua atribut visual ke nilai kosong. |
| [resetInnerFacade](#resetInnerFacade--) | Setel ulang semua atribut visual dari facade internal ke nilai kosong. |
| [save](#save--) | Menyimpan perubahan ke file tujuan. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF {@link PdfFormat}. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Mengatur nama file tujuan. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Mengatur aliran tujuan. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Mengatur opsi untuk kotak kombo dengan nilai ekspor. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Mengatur atribut visual dari bidang. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Atur gaya perataan bidang teks. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Atur gaya perataan vertikal bidang teks. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Atur atribut bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Mengatur jumlah kom untuk bidang teks satu baris reguler (bidang secara otomatis dibagi menjadi sebanyak posisi yang berjarak sama, atau kom, sesuai nilai parameter combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Mengatur jumlah karakter maksimum bidang teks. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Atur JavaScript untuk bidang PushButton. Jika JavaScript lama ada, itu akan diganti dengan yang baru. |
| [setItems](#setItems-java.lang.String:A-) | <p> Mengatur item yang akan ditambahkan ke kotak daftar atau kotak kombo yang baru dibuat. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Atur anggota untuk mencatat jarak antara dua tombol radio yang berdekatan dalam piksel, defaultnya 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Atur flag untuk menunjukkan apakah radio diatur secara horizontal atau vertikal, nilai default adalah true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mengatur opsi penyimpanan saat hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Mengatur nama file sumber. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Mengatur aliran sumber. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Atur flag submit tombol submit. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Atur flag pengiriman tombol submit |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Mengatur URL tombol. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Ubah bidang teks satu baris menjadi beberapa baris. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Konstruktor untuk FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Tambahkan bidang dengan tipe yang ditentukan ke formulir. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Tambahkan bidang dengan tipe yang ditentukan ke formulir.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Tambahkan JavaScript untuk bidang PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Menambahkan item baru ke kotak daftar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Tambahkan item baru dengan nilai Export ke bidang kotak daftar yang ada, hanya untuk bidang combo box AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Tambahkan tombol submit pada formulir. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Tutup instance objek

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Menyalin bidang yang ada ke posisi yang sama pada nomor halaman yang ditentukan. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali bidang yang baru disalin.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Menyalin bidang yang ada ke posisi baru yang ditentukan oleh nomor halaman dan koordinat. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali bidang yang baru disalin.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat asli. Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan koordinat asli. Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat yang ditentukan. Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Mengubah atribut visual semua bidang dalam dokumen PDF. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // menghias semua bidang. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Mengubah atribut visual semua bidang dalam dokumen PDF. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // menghias semua bidang. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Mengubah atribut visual semua bidang dalam dokumen PDF. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // menghias semua bidang. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Hapus item dari bidang daftar. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Tutup instance objek Metode ini sudah usang, gunakan close() sebagai gantinya.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

**Returns:**
Objek String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Mendapatkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline.

**Returns:**
Elemen ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Mendapatkan nama file tujuan.

**Returns:**
objek string

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Mendapatkan aliran tujuan. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

**Returns:**
objek OutputStream

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Mendapatkan dokumen {@code FormEditor} yang sedang diproses.

**Returns:**
objek IDocument

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Mendapatkan opsi untuk combo box dengan nilai ekspor. </p> <hr>

**Returns:**
Objek String[][]

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Mendapatkan atribut visual dari bidang.

**Returns:**
Objek FormFieldFacade

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Dapatkan flag bidang.

### getItems {#getItems--}
```
public String [] getItems()
```

Dapatkan Item yang akan ditambahkan ke list box atau combo box yang baru dibuat.

**Returns:**
objek String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Returns:**
nilai double

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Dapatkan anggota untuk mencatat jarak antara dua tombol radio berdekatan dalam piksel, defaultnya 50.

**Returns:**
nilai float

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

<p> Dapatkan flag untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true.

**Returns:**
nilai boolean

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions.

**Returns:**
Objek SaveOptions

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Mendapatkan nama file sumber.

**Returns:**
objek string

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Mendapatkan aliran sumber.

**Returns:**
Objek InputStream

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Dapatkan flag pengiriman tombol submit

**Returns:**
Elemen SubmitFormFlag @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Atur posisi baru bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Hapus bidang dari formulir. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Hapus aksi submit dari bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Ubah nama bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.renameField("textField", "textField_Renamed"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Setel ulang semua atribut visual ke nilai kosong.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Setel ulang semua atribut visual dari facade internal ke nilai kosong.

### save {#save--}
```
@Deprecated public void save()
```

Menyimpan perubahan ke file tujuan.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Mengatur cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF {@link PdfFormat}. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Mengatur nama file tujuan. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Mengatur aliran tujuan. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Mengatur opsi untuk kotak kombo dengan nilai ekspor. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Mengatur atribut visual dari bidang. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Atur gaya perataan bidang teks. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Atur gaya perataan vertikal bidang teks. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Atur flag bidang </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Atur atribut bidang. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Mengatur jumlah kom untuk bidang teks satu baris reguler (bidang secara otomatis dibagi menjadi sebanyak posisi yang berjarak sama, atau kom, sesuai nilai parameter combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Mengatur jumlah karakter maksimum bidang teks. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Atur JavaScript untuk bidang PushButton. Jika JavaScript lama ada, itu akan diganti dengan yang baru.

### setItems {#setItems-java.lang.String:A-}
<p> Mengatur item yang akan ditambahkan ke kotak daftar atau kotak kombo yang baru dibuat. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Atur anggota untuk mencatat jarak antara dua tombol radio yang berdekatan dalam piksel, defaultnya 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Atur flag untuk menunjukkan apakah radio diatur secara horizontal atau vertikal, nilai default adalah true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mengatur opsi penyimpanan saat hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Mengatur nama file sumber. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Mengatur aliran sumber. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Atur flag submit tombol submit. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Atur flag pengiriman tombol submit

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Mengatur URL tombol. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Ubah bidang teks satu baris menjadi beberapa baris. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre>
