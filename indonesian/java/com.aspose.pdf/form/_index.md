---
title: "Formulir"
linktitle: "Formulir"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili objek formulir."
type: docs
weight: 1740
url: /id/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Kelas yang mewakili objek formulir.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Menambahkan bidang pada formulir. |
| [add](#add-com.aspose.pdf.Field-int-) | Menambahkan bidang pada formulir. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Menambahkan bidang baru ke formulir; Jika bidang ini sudah ditempatkan pada formulir lain atau formulir ini, salinan bidang akan dibuat. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Menambahkan bidang pada formulir. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Menambahkan tampilan tambahan bidang ke halaman tertentu dari dokumen pada lokasi yang ditentukan. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Menambahkan tampilan tambahan bidang ke halaman tertentu dari dokumen. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Mengatur XFA formulir ke nilai yang ditentukan. |
| [clear](#clear--) | Menghapus semua bidang dari formulir. Tidak didukung. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Menentukan apakah bidang ditampilkan pada formulir.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Menyalin bidang yang ditempatkan pada formulir ke dalam array. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Menyalin bidang formulir ke array. |
| [delete](#delete-com.aspose.pdf.Field-) | Hapus bidang dari formulir. |
| [delete](#delete-java.lang.String-) | Menghapus bidang dari formulir berdasarkan namanya. |
| [flatten](#flatten--) | Menghapus semua bidang formulir statis dan menempatkan nilainya langsung pada halaman. |
| [get_Item](#get_Item-int-) | Mendapatkan bidang formulir berdasarkan indeks bidang. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan bidang formulir berdasarkan nama bidang. Melempar pengecualian jika bidang tidak ditemukan. |
| [get_xfa](#get_xfa--) | Hanya untuk penggunaan internal |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Mencari bidang berdasarkan nama bidang. Mengembalikan null jika bidang tidak ditemukan. |
| [getAutoRecalculate](#getAutoRecalculate--) | Jika diatur, semua bidang formulir akan dihitung ulang ketika ada bidang yang berubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi formulir dengan banyak bidang yang dihitung. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Jika diatur, bidang formulir yang tidak ada akan secara otomatis dibuat jika mereka ada dalam anotasi. |
| [getDefaultAppearance](#getDefaultAppearance--) | Mendapatkan tampilan default formulir (objek yang menggambarkan font default, ukuran teks, dan warna untuk bidang pada formulir). |
| [getDefaultResources](#getDefaultResources--) | Mendapatkan sumber daya default yang ditempatkan pada formulir ini. |
| [getDocument](#getDocument--) | Hanya untuk penggunaan internal |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Jika properti ini bernilai true maka persegi panjang batas merah tambahan akan digambar untuk kontainer elemen Xfa exclGroup yang diperlukan. Properti ini diperkenalkan karena tidak adanya analogi untuk exclGroup selama konversi representasi Xfa formulir ke standar. Nilainya false secara default. |
| [getFields](#getFields--) | Mendapatkan daftar semua bidang pada tingkat terendah dari formulir hierarkis. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Mengembalikan bidang di dalam persegi panjang yang ditentukan. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Jika properti ini bernilai true, nilai kunci NeedsRendering akan diabaikan selama konversi formulir XFA ke formulir Standar. Nilainya false secara default. |
| [getNeedsRendering](#getNeedsRendering--) | Mendapatkan nilai yang menunjukkan apakah dokumen memerlukan penghapusan formulir XFA dinamis. Properti ini diperkenalkan untuk menentukan apakah {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) harus digunakan untuk menghapus formulir XFA dalam kasus di mana formulir XFA hadir dan {@code NeedsRendering}({@link #getNeedsRendering}) bernilai false. |
| [getRemovePermission](#getRemovePermission--) | Jika properti ini bernilai true, kamus "Perms" akan dihapus dari dokumen pdf setelah konversi dokumen dinamis ke standar. Kamus "Perms" dapat berisi aturan yang mengganggu tampilan pilihan bidang wajib di Adobe Acrobat Reader. Nilainya false secara default. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Jika diatur, dokumen berisi tanda tangan yang mungkin menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, bukan sebagai pembaruan inkremental. |
| [getSignaturesExist](#getSignaturesExist--) | Jika diatur, dokumen berisi setidaknya satu bidang tanda tangan. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Formulir dapat berisi informasi penandatanganan, misalnya dapat ditandatangani atau tidak ditandatangani. Dan tampilan formulir kadang harus bergantung pada apakah formulir ditandatangani atau tidak. Properti ini memberi tahu konverter formulir (misalnya selama konversi formulir XFA ke formulir Standar) apakah formulir hasil harus dirender sebagai ditandatangani atau tidak ditandatangani. |
| [getSyncRoot](#getSyncRoot--) | Mengembalikan objek sinkronisasi. |
| [getType](#getType--) | Mendapatkan tipe formulir. Nilai yang mungkin: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Mendapatkan data XFA dari formulir (jika ada). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Periksa apakah formulir sudah memiliki bidang yang ditentukan. |
| [hasField](#hasField-java.lang.String-) | Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Formulir. |
| [hasField](#hasField-java.lang.String-boolean-) | Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Formulir, dengan kemampuan untuk melihat hierarki anak bidang. |
| [hasXfa](#hasXfa--) | Mendapatkan nilai yang menunjukkan apakah dokumen berisi formulir XFA. Properti ini diperkenalkan untuk menentukan apakah {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) harus digunakan untuk menghapus formulir XFA dalam kasus di mana formulir XFA hadir dan {@code NeedsRendering}({@link #getNeedsRendering}) bernilai false. |
| [isReadOnly](#isReadOnly--) | Menentukan apakah koleksi bersifat readonly. Selalu mengembalikan false. |
| [isSynchronized](#isSynchronized--) | Mengembalikan true jika objek bersifat thread-safe. |
| [iterator](#iterator--) | Mendapatkan enumerasi bidang formulir. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke aliran yang disediakan. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Menghapus bidang dari formulir. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Menghapus tampilan bidang pada indeks yang ditentukan. Jika hanya satu tampilan anak yang tersisa, metode menyematkannya ke dalam bidang. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Jika diatur, semua bidang formulir akan dihitung ulang ketika ada bidang yang berubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi formulir dengan banyak bidang yang dihitung. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Jika diatur, bidang formulir yang tidak ada akan secara otomatis dibuat jika mereka ada dalam anotasi. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Memungkinkan untuk mengatur urutan perhitungan bidang. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Mengatur tampilan default formulir (objek yang menggambarkan font default, ukuran teks, dan warna untuk bidang pada formulir). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Jika properti ini bernilai true maka persegi panjang batas merah tambahan akan digambar untuk kontainer elemen Xfa exclGroup yang diperlukan. Properti ini diperkenalkan karena tidak adanya analogi untuk exclGroup selama konversi representasi Xfa formulir ke standar. Nilainya false secara default. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Jika properti ini bernilai true, nilai kunci NeedsRendering akan diabaikan selama konversi formulir XFA ke formulir Standar. Nilainya false secara default. |
| [setRemovePermission](#setRemovePermission-boolean-) | Jika properti ini bernilai true, kamus "Perms" akan dihapus dari dokumen pdf setelah konversi dokumen dinamis ke standar. Kamus "Perms" dapat berisi aturan yang mengganggu tampilan pilihan bidang wajib di Adobe Acrobat Reader. Nilainya false secara default. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Jika diatur, dokumen berisi tanda tangan yang mungkin menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, bukan sebagai pembaruan inkremental. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Jika diatur, dokumen berisi setidaknya satu bidang tanda tangan. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Formulir dapat berisi informasi penandatanganan, misalnya dapat ditandatangani atau tidak ditandatangani. Dan tampilan formulir kadang harus bergantung pada apakah formulir ditandatangani atau tidak. Properti ini memberi tahu konverter formulir (misalnya selama konversi formulir XFA ke formulir Standar) apakah formulir hasil harus dirender sebagai ditandatangani atau tidak ditandatangani. |
| [setType](#setType-com.aspose.pdf.FormType-) | Mendapatkan tipe formulir. Nilai yang mungkin: Standard, Static, Dynamic. |
| [size](#size--) | Mendapatkan jumlah bidang pada formulir ini. |

### Form {#Form-com.aspose.pdf.IDocument-}
Konstruktor

### add {#add-com.aspose.pdf.Field-}
Menambahkan bidang pada formulir.

### add {#add-com.aspose.pdf.Field-int-}
Menambahkan bidang pada formulir.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Menambahkan bidang baru ke formulir; Jika bidang ini sudah ditempatkan pada formulir lain atau formulir ini, salinan bidang akan dibuat.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Menambahkan bidang pada formulir.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Menambahkan tampilan tambahan bidang ke halaman tertentu dari dokumen pada lokasi yang ditentukan.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Menambahkan tampilan tambahan bidang ke halaman tertentu dari dokumen.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Mengatur XFA formulir ke nilai yang ditentukan.

### clear {#clear--}
```
public void clear()
```

Menghapus semua bidang dari formulir. Tidak didukung.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Menentukan apakah bidang ditampilkan pada formulir..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Menyalin bidang yang ditempatkan pada formulir ke dalam array.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Menyalin bidang formulir ke array.

### delete {#delete-com.aspose.pdf.Field-}
Hapus bidang dari formulir.

### delete {#delete-java.lang.String-}
Menghapus bidang dari formulir berdasarkan namanya.

### flatten {#flatten--}
```
public void flatten()
```

Menghapus semua bidang formulir statis dan menempatkan nilainya langsung pada halaman.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Mendapatkan bidang formulir berdasarkan indeks bidang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks bidang. |

**Returns:**
Bidang yang diambil.

### get_Item {#get_Item-java.lang.String-}
Mendapatkan bidang formulir berdasarkan nama bidang. Melempar pengecualian jika bidang tidak ditemukan.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Hanya untuk penggunaan internal

**Returns:**
objek XFA

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  |  |

### get {#get-java.lang.String-}
Mencari bidang berdasarkan nama bidang. Mengembalikan null jika bidang tidak ditemukan.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Jika diatur, semua bidang formulir akan dihitung ulang ketika ada bidang yang berubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi formulir dengan banyak bidang yang dihitung.

**Returns:**
nilai boolean

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Jika diatur, bidang formulir yang tidak ada akan secara otomatis dibuat jika mereka ada dalam anotasi.

**Returns:**
nilai boolean

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Mendapatkan tampilan default formulir (objek yang menggambarkan font default, ukuran teks, dan warna untuk bidang pada formulir).

**Returns:**
objek DefaultAppearance

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Mendapatkan sumber daya default yang ditempatkan pada formulir ini.

**Returns:**
nilai Resources

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Hanya untuk penggunaan internal

**Returns:**
objek IDocument

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Jika properti ini bernilai true maka persegi panjang batas merah tambahan akan digambar untuk kontainer elemen Xfa exclGroup yang diperlukan. Properti ini diperkenalkan karena tidak adanya analogi untuk exclGroup selama konversi representasi Xfa formulir ke standar. Nilainya false secara default.

**Returns:**
nilai boolean

### getFields {#getFields--}
```
public Field [] getFields()
```

Mendapatkan daftar semua bidang pada tingkat terendah dari formulir hierarkis.

**Returns:**
Array dengan bidang yang ditemukan.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Mengembalikan bidang di dalam persegi panjang yang ditentukan.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Jika properti ini bernilai true, nilai kunci NeedsRendering akan diabaikan selama konversi formulir XFA ke formulir Standar. Nilainya false secara default.

**Returns:**
nilai boolean

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Mendapatkan nilai yang menunjukkan apakah dokumen memerlukan penghapusan formulir XFA dinamis. Properti ini diperkenalkan untuk menentukan apakah {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) harus digunakan untuk menghapus formulir XFA dalam kasus di mana formulir XFA hadir dan {@code NeedsRendering}({@link #getNeedsRendering}) bernilai false.

**Returns:**
nilai boolean

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Jika properti ini bernilai true, kamus "Perms" akan dihapus dari dokumen pdf setelah konversi dokumen dinamis ke standar. Kamus "Perms" dapat berisi aturan yang mengganggu tampilan pilihan bidang wajib di Adobe Acrobat Reader. Nilainya false secara default.

**Returns:**
nilai boolean

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Jika diatur, dokumen berisi tanda tangan yang mungkin menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, bukan sebagai pembaruan inkremental.

**Returns:**
nilai boolean

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Jika diatur, dokumen berisi setidaknya satu bidang tanda tangan.

**Returns:**
nilai boolean

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Formulir dapat berisi informasi penandatanganan, misalnya dapat ditandatangani atau tidak ditandatangani. Dan tampilan formulir kadang harus bergantung pada apakah formulir ditandatangani atau tidak. Properti ini memberi tahu konverter formulir (misalnya selama konversi formulir XFA ke formulir Standar) apakah formulir hasil harus dirender sebagai ditandatangani atau tidak ditandatangani.

**Returns:**
elemen SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mengembalikan objek sinkronisasi.

**Returns:**
Objek untuk sinkronisasi

### getType {#getType--}
```
public FormType getType()
```

Mendapatkan tipe formulir. Nilai yang mungkin: Standard, Static, Dynamic.

**Returns:**
nilai FormType @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Mendapatkan data XFA dari formulir (jika ada).

**Returns:**
nilai XFA

### hasField {#hasField-com.aspose.pdf.Field-}
Periksa apakah formulir sudah memiliki bidang yang ditentukan.

### hasField {#hasField-java.lang.String-}
Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Formulir.

### hasField {#hasField-java.lang.String-boolean-}
Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Formulir, dengan kemampuan untuk melihat hierarki anak bidang.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Mendapatkan nilai yang menunjukkan apakah dokumen berisi formulir XFA. Properti ini diperkenalkan untuk menentukan apakah {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) harus digunakan untuk menghapus formulir XFA dalam kasus di mana formulir XFA hadir dan {@code NeedsRendering}({@link #getNeedsRendering}) bernilai false.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Menentukan apakah koleksi bersifat readonly. Selalu mengembalikan false.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mengembalikan true jika objek bersifat thread-safe.

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Mendapatkan enumerasi bidang formulir.

**Returns:**
enumerator bidang.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke aliran yang disediakan. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Menghapus bidang dari formulir.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Menghapus tampilan bidang pada indeks yang ditentukan. Jika hanya satu tampilan anak yang tersisa, metode menyematkannya ke dalam bidang.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Jika diatur, semua bidang formulir akan dihitung ulang ketika ada bidang yang berubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi formulir dengan banyak bidang yang dihitung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Jika diatur, bidang formulir yang tidak ada akan secara otomatis dibuat jika mereka ada dalam anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Memungkinkan untuk mengatur urutan perhitungan bidang.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Mengatur tampilan default formulir (objek yang menggambarkan font default, ukuran teks, dan warna untuk bidang pada formulir).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Jika properti ini bernilai true maka persegi panjang batas merah tambahan akan digambar untuk kontainer elemen Xfa exclGroup yang diperlukan. Properti ini diperkenalkan karena tidak adanya analogi untuk exclGroup selama konversi representasi Xfa formulir ke standar. Nilainya false secara default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Jika properti ini bernilai true, nilai kunci NeedsRendering akan diabaikan selama konversi formulir XFA ke formulir Standar. Nilainya false secara default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Jika properti ini bernilai true, kamus "Perms" akan dihapus dari dokumen pdf setelah konversi dokumen dinamis ke standar. Kamus "Perms" dapat berisi aturan yang mengganggu tampilan pilihan bidang wajib di Adobe Acrobat Reader. Nilainya false secara default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Jika diatur, dokumen berisi tanda tangan yang mungkin menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, bukan sebagai pembaruan inkremental.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Jika diatur, dokumen berisi setidaknya satu bidang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Formulir dapat berisi informasi penandatanganan, misalnya dapat ditandatangani atau tidak ditandatangani. Dan tampilan formulir kadang harus bergantung pada apakah formulir ditandatangani atau tidak. Properti ini memberi tahu konverter formulir (misalnya selama konversi formulir XFA ke formulir Standar) apakah formulir hasil harus dirender sebagai ditandatangani atau tidak ditandatangani.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | elemen SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Mendapatkan tipe formulir. Nilai yang mungkin: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Mendapatkan jumlah bidang pada formulir ini.

**Returns:**
nilai int
