---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk mengedit halaman file PDF, termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman."
type: docs
weight: 570
url: /id/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Mewakili kelas untuk mengedit halaman file PDF, termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman.

## Fields

| Field | Deskripsi |
| --- | --- |
| [BLINDH](#BLINDH) | Tirai Vertikal |
| [BLINDV](#BLINDV) | Tirai Vertikal |
| [BTWIPE](#BTWIPE) | Usap Bawah-Atas |
| [DGLITTER](#DGLITTER) | Kilau Diagonal |
| [DISSOLVE](#DISSOLVE) | Halaman lama menghilang |
| [INBOX](#INBOX) | Kotak Masuk |
| [LRGLITTER](#LRGLITTER) | Kilau Kiri-Kanan |
| [LRWIPE](#LRWIPE) | Usap Kiri-Kanan |
| [OUTBOX](#OUTBOX) | Kotak Keluar |
| [RLWIPE](#RLWIPE) | Usap Kanan-Kiri |
| [SPLITHIN](#SPLITHIN) | Pemisahan Horizontal MASUK |
| [SPLITHOUT](#SPLITHOUT) | Pemisahan Horizontal KELUAR |
| [SPLITVIN](#SPLITVIN) | Pemisahan Vertikal MASUK |
| [SPLITVOUT](#SPLITVOUT) | Pemisahan Vertikal KELUAR |
| [TBGLITTER](#TBGLITTER) | Kilau Atas-Bawah |
| [TBWIPE](#TBWIPE) | Usap Atas-Bawah |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Konstruktor untuk kelas PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Konstruktor untuk kelas PdfPageEditor. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyChanges](#applyChanges--) | Terapkan perubahan yang dibuat pada halaman dokumen. |
| [getAlignment](#getAlignment--) | Mendapatkan perataan horizontal dari konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. Gunakan getHorizontalAlignment sebagai gantinya |
| [getDisplayDuration](#getDisplayDuration--) | Mendapatkan durasi tampilan untuk halaman. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan perataan horizontal dari konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Mengembalikan ukuran kotak yang ditentukan dalam dokumen. </p> <hr> <pre> Contoh berikut menunjukkan cara mendapatkan media box dari halaman pertama: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Kembalikan ukuran halaman. |
| [getPageRotation](#getPageRotation-int-) | <p> Mengembalikan rotasi halaman yang ditentukan. </p> <hr> <pre> Contoh berikut menunjukkan cara mendapatkan rotasi halaman: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Mendapatkan rotasi halaman, sebuah hashtable berisi nomor halaman dan derajat rotasi, kunci mewakili nomor halaman, nilai kunci mewakili rotasi dalam derajat. </p> |
| [getPages](#getPages--) | <p> Mengembalikan total jumlah halaman. </p> <hr> <pre> Contoh berikut menunjukkan penggunaan metode GetPages(): PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Mendapatkan ukuran halaman file output. |
| [getPageSize](#getPageSize-int-) | <p> Mengembalikan ukuran halaman dari halaman yang ditentukan. </p> <hr> <pre> Contoh berikut menunjukkan penggunaan metode GetPageSize: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Mendapatkan nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit. |
| [getRotation](#getRotation--) | Mendapatkan rotasi halaman, rotasi harus 0, 90, 180, atau 270. Nilai default adalah 0. |
| [getTransitionDuration](#getTransitionDuration--) | Mendapatkan durasi efek transisi. |
| [getTransitionType](#getTransitionType--) | Mendapatkan gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. Gunakan getVerticalAlignmentType sebagai gantinya |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Mendapatkan perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Dapatkan koefisien zoom. Nilai 1.0 sesuai dengan 100%. Nilai default adalah 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Periksa apakah kotak didefinisikan pada halaman. |
| [movePosition](#movePosition-float-float-) | <p> Memindahkan asal dari (0, 0) ke titik yang ditunjuk. Asal berada di kiri-bawah dan satuannya adalah point (1 inci = 72 point). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Menyimpan dokumen yang diubah ke dalam stream. </p> <hr> <pre> Contoh berikut menunjukkan cara menyimpan dokumen PDF yang diubah ke dalam stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Menyimpan dokumen yang diubah ke dalam file. </p> <hr> <pre> Contoh berikut menunjukkan cara menyimpan dokumen PDF yang diubah PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. Gunakan setHorizontalAlignment sebagai gantinya |
| [setDisplayDuration](#setDisplayDuration-int-) | Mengatur durasi tampilan untuk halaman. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Mengatur rotasi halaman, sebuah hashtable berisi nomor halaman dan derajat rotasi, kunci mewakili nomor halaman, nilai kunci mewakili rotasi dalam derajat. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Mengatur ukuran halaman file output. |
| [setProcessPages](#setProcessPages-int:A-) | Mengatur nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit. |
| [setRotation](#setRotation-int-) | Mengatur rotasi halaman, rotasi harus 0, 90, 180, atau 270. Nilai default adalah 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Mengatur durasi efek transisi. |
| [setTransitionType](#setTransitionType-int-) | Mengatur gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. Gunakan setVerticalAlignmentType sebagai gantinya |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Mengatur koefisien zoom. Nilai 1.0 sesuai dengan 100%. Nilai default adalah 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Tirai Vertikal

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Tirai Vertikal

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Usap Bawah-Atas

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Kilau Diagonal

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

Halaman lama menghilang

### INBOX {#INBOX}
```
public static final int INBOX
```

Kotak Masuk

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Kilau Kiri-Kanan

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Usap Kiri-Kanan

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Kotak Keluar

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Usap Kanan-Kiri

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

Pemisahan Horizontal MASUK

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Pemisahan Horizontal KELUAR

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

Pemisahan Vertikal MASUK

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Pemisahan Vertikal KELUAR

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Kilau Atas-Bawah

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Usap Atas-Bawah

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Konstruktor untuk kelas PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Konstruktor untuk kelas PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Terapkan perubahan yang dibuat pada halaman dokumen.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Mendapatkan perataan horizontal dari konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. Gunakan getHorizontalAlignment sebagai gantinya

**Returns:**
Objek AlignmentType @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Mendapatkan durasi tampilan untuk halaman.

**Returns:**
nilai int

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Mendapatkan perataan horizontal dari konten PDF asli pada halaman hasil, default adalah AlignmentType.Left.

**Returns:**
Elemen HorizontalAlignment @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Mengembalikan ukuran kotak yang ditentukan dalam dokumen. </p> <hr> <pre> Contoh berikut menunjukkan cara mendapatkan media box dari halaman pertama: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Kembalikan ukuran halaman.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Mengembalikan rotasi halaman yang ditentukan. </p> <hr> <pre> Contoh berikut menunjukkan cara mendapatkan rotasi halaman: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman |  | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |

**Returns:**
Rotasi halaman dalam derajat.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Mendapatkan rotasi halaman, sebuah hashtable berisi nomor halaman dan derajat rotasi, kunci mewakili nomor halaman, nilai kunci mewakili rotasi dalam derajat. </p>

**Returns:**
Objek {@code Map<Integer, Integer>}

### getPages {#getPages--}
```
public int getPages()
```

<p> Mengembalikan total jumlah halaman. </p> <hr> <pre> Contoh berikut menunjukkan penggunaan metode GetPages(): PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Jumlah halaman.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Mendapatkan ukuran halaman file output.

**Returns:**
Objek PageSize

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Mengembalikan ukuran halaman dari halaman yang ditentukan. </p> <hr> <pre> Contoh berikut menunjukkan penggunaan metode GetPageSize: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman |  | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |

**Returns:**
Hasil adalah instance dari PageSize. Gunakan properti Width dan Height dari objek yang dikembalikan untuk mendapatkan lebar dan tinggi halaman.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Mendapatkan nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit.

**Returns:**
array nilai int

### getRotation {#getRotation--}
```
public int getRotation()
```

Mendapatkan rotasi halaman, rotasi harus 0, 90, 180, atau 270. Nilai default adalah 0.

**Returns:**
nilai int

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Mendapatkan durasi efek transisi.

**Returns:**
nilai int

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Mendapatkan gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi.

**Returns:**
nilai int

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Mendapatkan perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. Gunakan getVerticalAlignmentType sebagai gantinya

**Returns:**
Objek VerticalAlignmentType

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Mendapatkan perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom.

**Returns:**
Elemen VerticalAlignmentType @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Dapatkan koefisien zoom. Nilai 1.0 sesuai dengan 100%. Nilai default adalah 1.0.

**Returns:**
nilai float

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Periksa apakah kotak didefinisikan pada halaman.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Memindahkan asal dari (0, 0) ke titik yang ditunjuk. Asal berada di kiri-bawah dan satuannya adalah point (1 inci = 72 point). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| moveX |  | Koordinat X. |
| moveY |  | Koordinat Y. |

### save {#save-java.io.OutputStream-}
<p> Menyimpan dokumen yang diubah ke dalam stream. </p> <hr> <pre> Contoh berikut menunjukkan cara menyimpan dokumen PDF yang diubah ke dalam stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Menyimpan dokumen yang diubah ke dalam file. </p> <hr> <pre> Contoh berikut menunjukkan cara menyimpan dokumen PDF yang diubah PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. Gunakan setHorizontalAlignment sebagai gantinya

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Mengatur durasi tampilan untuk halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Mengatur rotasi halaman, sebuah hashtable berisi nomor halaman dan derajat rotasi, kunci mewakili nomor halaman, nilai kunci mewakili rotasi dalam derajat.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Mengatur ukuran halaman file output.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Mengatur nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array nilai int |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Mengatur rotasi halaman, rotasi harus 0, 90, 180, atau 270. Nilai default adalah 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Mengatur durasi efek transisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Mengatur gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. Gunakan setVerticalAlignmentType sebagai gantinya

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Mengatur koefisien zoom. Nilai 1.0 sesuai dengan 100%. Nilai default adalah 1.0. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float <hr> <pre> Contoh berikut menunjukkan cara mengubah zoom halaman dokumen. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
