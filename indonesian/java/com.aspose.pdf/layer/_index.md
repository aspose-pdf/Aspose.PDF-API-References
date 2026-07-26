---
title: "Layer"
linktitle: "Layer"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili lapisan dalam halaman PDF."
type: docs
weight: 2640
url: /id/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Mewakili lapisan dalam halaman PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas {@code Layer}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [delete](#delete--) | Menghapus lapisan saat ini dari dokumen PDF. |
| [flatten](#flatten-boolean-) | Meratakan lapisan yang ditentukan. |
| [getContents](#getContents--) | <p> Mendapatkan konten lapisan. </p> |
| [getDefaultState](#getDefaultState--) | Mendapatkan status default lapisan PDF. |
| [getId](#getId--) | Mendapatkan id lapisan. |
| [getLocked](#getLocked--) | Mendapatkan nilai yang menunjukkan apakah lapisan terkunci. |
| [getName](#getName--) | Mendapatkan nama lapisan. |
| [lock](#lock--) | Mengunci lapisan. |
| [save](#save-java.io.OutputStream-) | Menyimpan lapisan saat ini ke dokumen PDF. |
| [save](#save-java.lang.String-) | Menyimpan lapisan saat ini ke dokumen PDF. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Mengatur status default lapisan PDF. |
| [unlock](#unlock--) | Membuka kunci lapisan. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Menginisialisasi instance baru dari kelas {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

Menghapus lapisan saat ini dari dokumen PDF.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Meratakan lapisan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cleanupContentStream |  | Menentukan apakah akan menghapus penanda grup konten opsional dari aliran konten. Menetapkan parameter {@code cleanupContentStream} ke false mempercepat proses perataan. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Mendapatkan konten lapisan. </p>

**Returns:**
objek {@code List<Operator>}

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Mendapatkan status default lapisan PDF.

**Returns:**
status default lapisan PDF.

### getId {#getId--}
```
public String getId()
```

Mendapatkan id lapisan.

**Returns:**
nilai String

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Mendapatkan nilai yang menunjukkan apakah lapisan terkunci.

**Returns:**
nilai boolean

### getName {#getName--}
```
public String getName()
```

Mendapatkan nama lapisan.

**Returns:**
nilai String

### lock {#lock--}
```
public final void lock()
```

Mengunci lapisan.

### save {#save-java.io.OutputStream-}
Menyimpan lapisan saat ini ke dokumen PDF.

### save {#save-java.lang.String-}
Menyimpan lapisan saat ini ke dokumen PDF.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Mengatur status default lapisan PDF.

### unlock {#unlock--}
```
public final void unlock()
```

Membuka kunci lapisan.
