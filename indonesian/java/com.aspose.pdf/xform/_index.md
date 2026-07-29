---
title: "XForm"
linktitle: "XForm"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas mewakili XForm"
type: docs
weight: 5590
url: /id/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Kelas mewakili XForm

## Metode

| Metode | Deskripsi |
| --- | --- |
| [close](#close--) | Membebaskan memori |
| [containsOwnResources](#containsOwnResources--) | Mengembalikan True jika berisi Sumber Daya Milik Sendiri |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Membuat XForm baru dalam dokumen. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Membuat XForm yang menggandakan isi halaman. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Membebaskan memori |
| [freeMemory](#freeMemory--) | Menghapus data yang di-cache |
| [getBBox](#getBBox--) | Mendapatkan kotak pembatas formulir. |
| [getContents](#getContents--) | Mendapatkan operator formulir. |
| [getEngineObj](#getEngineObj--) | Hanya internal |
| [getIT](#getIT--) | Mendapatkan Form IT. Form IT adalah nama yang menggambarkan maksud XObject. |
| [getMatrix](#getMatrix--) | Mendapatkan matriks formulir. |
| [getName](#getName--) | Mendapatkan nama formulir. Nama formulir adalah nama yang digunakan untuk merujuk formulir dalam kamus XObejct di sumber daya halaman. |
| [getOpi](#getOpi--) | Mendapatkan Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang formulir. |
| [getResources](#getResources--) | Mengembalikan sumber daya Form X-Object. Jika Form tidak memiliki sumber daya dan allowCreate bernilai true, Resources akan secara otomatis dibuat untuk formulir. |
| [getResources](#getResources-boolean-) | Mengembalikan sumber daya Form X-Object |
| [getResourcesField](#getResourcesField--) | Mendapatkan sumber daya Form XObject. |
| [getSubtype](#getSubtype--) | Mendapatkan Subtype formulir. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Mengatur kotak pembatas formulir. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Mengatur matriks formulir. |
| [setName](#setName-java.lang.String-) | Mengatur nama formulir. Nama formulir adalah nama yang digunakan untuk merujuk formulir dalam kamus XObejct di sumber daya halaman. |

### close {#close--}
```
public final void close()
```

Membebaskan memori

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Mengembalikan True jika berisi Sumber Daya Milik Sendiri

**Returns:**
nilai boolean

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Membuat XForm baru dalam dokumen.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Membuat XForm yang menggandakan isi halaman.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Membebaskan memori

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Menghapus data yang di-cache

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Mendapatkan kotak pembatas formulir.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Mendapatkan operator formulir.

**Returns:**
objek OperatorCollection

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Hanya internal

**Returns:**
Objek IPdfObject

### getIT {#getIT--}
```
public final String getIT()
```

Mendapatkan Form IT. Form IT adalah nama yang menggambarkan maksud XObject.

**Returns:**
nilai String

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Mendapatkan matriks formulir.

**Returns:**
Matriks

### getName {#getName--}
```
public String getName()
```

Mendapatkan nama formulir. Nama formulir adalah nama yang digunakan untuk merujuk formulir dalam kamus XObejct di sumber daya halaman.

**Returns:**
String

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Mendapatkan Open Prepress Interface (OPI).

**Returns:**
instansi Opi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang formulir.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Mengembalikan sumber daya Form X-Object. Jika Form tidak memiliki sumber daya dan allowCreate bernilai true, Resources akan secara otomatis dibuat untuk formulir.

**Returns:**
instansi Resources

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Mengembalikan sumber daya Form X-Object

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowCreate |  | Jika Form tidak memiliki sumber daya dan allowCreate bernilai true, Resources akan secara otomatis dibuat untuk formulir. |

**Returns:**
instansi Resources

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Mendapatkan sumber daya Form XObject.

**Returns:**
Instansi Resources. Jika Form tidak memiliki sumber daya, Resources akan secara otomatis dibuat untuk formulir.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Mendapatkan Subtype formulir.

**Returns:**
nilai String

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Mengatur kotak pembatas formulir.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Mengatur matriks formulir.

### setName {#setName-java.lang.String-}
Mengatur nama formulir. Nama formulir adalah nama yang digunakan untuk merujuk formulir dalam kamus XObejct di sumber daya halaman.
