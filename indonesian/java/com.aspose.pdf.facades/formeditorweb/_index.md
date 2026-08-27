---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk mengedit formulir (menambah/menghapus bidang, dll)"
type: docs
weight: 210
url: /id/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Kelas untuk mengedit formulir (menambah/menghapus bidang, dll)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Tambahkan bidang dengan tipe yang ditentukan ke formulir. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Tambahkan bidang dengan tipe yang ditentukan ke formulir. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Tambahkan JavaScript untuk bidang PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Menambahkan item baru ke kotak daftar. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Tambahkan item baru dengan nilai Export ke bidang kotak daftar yang ada, hanya untuk bidang kotak kombo AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Tambahkan tombol submit pada formulir. |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Menyalin bidang yang ada ke posisi yang sama pada nomor halaman yang ditentukan. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Menyalin bidang yang ada ke posisi baru yang ditentukan oleh nomor halaman dan ordinat. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat asli. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat asli. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat. |
| [decorateField](#decorateField--) | Mengubah atribut visual semua bidang dalam dokumen PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Mengubah atribut visual semua bidang dengan tipe bidang yang ditentukan. |
| [decorateField](#decorateField-java.lang.String-) | Mengubah atribut visual bidang yang ditentukan. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Hapus item dari bidang daftar. |
| [dispose](#dispose--) | Usang. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [getDestFileName](#getDestFileName--) | Usang. |
| [getDestStream](#getDestStream--) | Mendapatkan aliran tujuan. |
| [getExportItems](#getExportItems--) | Mendapatkan opsi untuk kotak kombo dengan nilai ekspor. |
| [getFacade](#getFacade--) | Mendapatkan atribut visual dari bidang. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Dapatkan flag bidang. |
| [getItems](#getItems--) | Mengembalikan array item |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). |
| [getRadioGap](#getRadioGap--) | Dapatkan anggota untuk mencatat jarak antara dua tombol radio berdekatan dalam piksel, defaultnya 50. |
| [getRadioHoriz](#getRadioHoriz--) | Ambil flag untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true. |
| [getResponse](#getResponse--) | Mendapatkan objek Response dimana hasil operasi akan disimpan. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Usang. |
| [getSrcStream](#getSrcStream--) | Mendapatkan aliran sumber. |
| [getSubmitFlag](#getSubmitFlag--) | Dapatkan flag pengiriman tombol submit |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Atur posisi baru bidang. |
| [removeField](#removeField-java.lang.String-) | Hapus bidang dari formulir. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Hapus aksi submit dari bidang. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Ubah nama bidang. |
| [resetFacade](#resetFacade--) | Setel ulang semua atribut visual ke nilai kosong. |
| [resetInnerFacade](#resetInnerFacade--) | Setel ulang semua atribut visual dari fasad internal ke nilai kosong. |
| [save](#save--) | Menyimpan perubahan ke file tujuan. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Usang. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Mengatur aliran tujuan. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Mengatur opsi untuk kotak kombo dengan nilai ekspor. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Mengatur atribut visual bidang. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Mengatur gaya perataan bidang teks. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Mengatur gaya perataan vertikal bidang teks. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Mengatur flag bidang |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Mengatur atribut bidang. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Mengatur jumlah comb untuk bidang teks satu baris reguler (bidang secara otomatis dibagi menjadi sebanyak posisi yang sama jaraknya, atau comb, sesuai nilai parameter combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Mengatur jumlah maksimum karakter bidang teks. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Mengatur JavaScript untuk bidang PushButton. |
| [setItems](#setItems-java.lang.String:A-) | Mengatur item yang akan ditambahkan ke list box atau kotak kombo yang baru dibuat. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). |
| [setRadioGap](#setRadioGap-float-) | Mengatur anggota untuk merekam jarak antara dua tombol radio tetangga dalam piksel, defaultnya 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Mengatur flag untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Mengatur objek Response dimana hasil operasi akan disimpan. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Usang. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Mengatur aliran sumber. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Mengatur flag submit dari tombol submit. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Atur flag pengiriman tombol submit |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Mengatur URL tombol. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Mengubah bidang teks satu baris menjadi beberapa baris. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Konstruktor untuk FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Tambahkan bidang dengan tipe yang ditentukan ke formulir.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Tambahkan bidang dengan tipe yang ditentukan ke formulir.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Tambahkan JavaScript untuk bidang PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Menambahkan item baru ke kotak daftar.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Tambahkan item baru dengan nilai Export ke bidang kotak daftar yang ada, hanya untuk bidang kotak kombo AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Tambahkan tombol submit pada formulir.

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Menyalin bidang yang ada ke posisi yang sama pada nomor halaman yang ditentukan.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Menyalin bidang yang ada ke posisi baru yang ditentukan oleh nomor halaman dan ordinat.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat asli.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat asli.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat.

### decorateField {#decorateField--}
```
public void decorateField()
```

Mengubah atribut visual semua bidang dalam dokumen PDF.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Mengubah atribut visual semua bidang dengan tipe bidang yang ditentukan.

### decorateField {#decorateField-java.lang.String-}
Mengubah atribut visual bidang yang ditentukan.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Hapus item dari bidang daftar.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Usang.

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

Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

**Returns:**
Elemen ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Usang.

**Returns:**
nilai string

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Mendapatkan aliran tujuan.

**Returns:**
objek OutputStream

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Mendapatkan opsi untuk kotak kombo dengan nilai ekspor.

**Returns:**
Array String[][]

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

Mengembalikan array item

**Returns:**
objek String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan).

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

Ambil flag untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true.

**Returns:**
nilai boolean

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Mendapatkan objek Response dimana hasil operasi akan disimpan.

**Returns:**
Objek HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

**Returns:**
Objek SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Usang.

**Returns:**
nilai string

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
Elemen SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
Atur posisi baru bidang.

### removeField {#removeField-java.lang.String-}
Hapus bidang dari formulir.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Hapus aksi submit dari bidang.

### renameField {#renameField-java.lang.String-java.lang.String-}
Ubah nama bidang.

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Setel ulang semua atribut visual ke nilai kosong.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Setel ulang semua atribut visual dari fasad internal ke nilai kosong.

### save {#save--}
```
public void save()
```

Menyimpan perubahan ke file tujuan.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Usang.

### setDestStream {#setDestStream-java.io.OutputStream-}
Mengatur aliran tujuan.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Mengatur opsi untuk kotak kombo dengan nilai ekspor.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Mengatur atribut visual bidang.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Mengatur gaya perataan bidang teks.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Mengatur gaya perataan vertikal bidang teks.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Mengatur flag bidang

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Mengatur atribut bidang.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Mengatur jumlah comb untuk bidang teks satu baris reguler (bidang secara otomatis dibagi menjadi sebanyak posisi yang sama jaraknya, atau comb, sesuai nilai parameter combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Mengatur jumlah maksimum karakter bidang teks.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Mengatur JavaScript untuk bidang PushButton.

### setItems {#setItems-java.lang.String:A-}
Mengatur item yang akan ditambahkan ke list box atau kotak kombo yang baru dibuat.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Mengatur anggota untuk merekam jarak antara dua tombol radio tetangga dalam piksel, defaultnya 50.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Mengatur flag untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Mengatur objek Response dimana hasil operasi akan disimpan.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Usang.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Mengatur aliran sumber.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Mengatur flag submit dari tombol submit.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Atur flag pengiriman tombol submit

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Mengatur URL tombol.

### single2Multiple {#single2Multiple-java.lang.String-}
Mengubah bidang teks satu baris menjadi beberapa baris.
