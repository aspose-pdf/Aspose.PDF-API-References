---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili file tersemat."
type: docs
weight: 1510
url: /id/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Kelas yang mewakili file tersemat.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Buat spesifikasi file kosong baru. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Buat spesifikasi file kosong baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Hubungan file terkait. |
| [getCollectionItem](#getCollectionItem--) | Mendapatkan item koleksi dari spesifikasi file. |
| [getContents](#getContents--) | Mendapatkan file konten. |
| [getContentsInternal](#getContentsInternal--) | Mendapatkan file konten. |
| [getDescription](#getDescription--) | Mendapatkan teks yang terkait dengan spesifikasi file. |
| [getEncoding](#getEncoding--) | Mendapatkan format enkoding. Nilai yang mungkin: Zip - file dikompresi dengan ZIP, None - file tidak dikompresi. |
| [getEncryptedPayload](#getEncryptedPayload--) | Mendapatkan muatan terenkripsi. |
| [getEngineDict](#getEngineDict--) | Kamus PDF yang berisi informasi tentang file. Hanya internal |
| [getEngineObj](#getEngineObj--) | Hanya internal |
| [getFileSystem](#getFileSystem--) | Mendapatkan nama sistem file. |
| [getMIMEType](#getMIMEType--) | Mendapatkan subtipe file yang disematkan |
| [getName](#getName--) | Mendapatkan nama spesifikasi file. |
| [getParams](#getParams--) | Mendapatkan parameter file. |
| [getStreamContents](#getStreamContents--) | Mendapatkan isi file sebagai aliran. Isi tidak dimuat ke memori sehingga memungkinkan mengurangi penggunaan memori. Namun aliran ini tidak mendukung penempatan posisi dan properti Length. Jika Anda memerlukan fitur ini, silakan gunakan properti Contents sebagai gantinya. |
| [getUnicodeName](#getUnicodeName--) | Mendapatkan nama unicode spesifikasi file. |
| [getValue](#getValue-java.lang.String-) | Mendapatkan parameter khusus aplikasi. |
| [isIncludeContents](#isIncludeContents--) | Jika true, isi file akan disertakan dalam spesifikasi file. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Hubungan file terkait. |
| [setContents](#setContents-byte:A-) | Mengatur isi file. |
| [setContents](#setContents-java.io.InputStream-) | Mengatur isi file. |
| [setDescription](#setDescription-java.lang.String-) | Mengatur teks yang terkait dengan spesifikasi file. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Mengatur format enkoding. Nilai yang mungkin: Zip - file dikompresi dengan ZIP, None - file tidak dikompresi. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Mengatur nama sistem file. |
| [setIncludeContents](#setIncludeContents-boolean-) | Jika true, isi file akan disertakan dalam spesifikasi file. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Mengatur MIMEType. |
| [setName](#setName-java.lang.String-) | Mengatur nama spesifikasi file. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Mengatur parameter file. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Mengatur nama unicode spesifikasi file. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Mengatur parameter khusus aplikasi. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-java.lang.String-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Buat spesifikasi file kosong baru.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Buat spesifikasi file kosong baru.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Hubungan file terkait.

**Returns:**
Elemen AFRelationship

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Mendapatkan item koleksi dari spesifikasi file.

**Returns:**
Instansi CollectionItem

### getContents {#getContents--}
```
public InputStream getContents()
```

Mendapatkan file konten.

**Returns:**
Objek InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Mendapatkan file konten.

**Returns:**
objek Stream

### getDescription {#getDescription--}
```
public String getDescription()
```

Mendapatkan teks yang terkait dengan spesifikasi file.

**Returns:**
nilai String

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Mendapatkan format enkoding. Nilai yang mungkin: Zip - file dikompresi dengan ZIP, None - file tidak dikompresi.

**Returns:**
nilai int @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Mendapatkan muatan terenkripsi.

**Returns:**
Instansi EncryptedPayload

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Kamus PDF yang berisi informasi tentang file. Hanya internal

**Returns:**
objek IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Hanya internal

**Returns:**
Objek IPdfObject

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Mendapatkan nama sistem file.

**Returns:**
nilai String

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Mendapatkan subtipe file yang disematkan

**Returns:**
nilai string

### getName {#getName--}
```
public String getName()
```

Mendapatkan nama spesifikasi file.

**Returns:**
nilai String

### getParams {#getParams--}
```
public FileParams getParams()
```

Mendapatkan parameter file.

**Returns:**
objek FileParams

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Mendapatkan isi file sebagai aliran. Isi tidak dimuat ke memori sehingga memungkinkan mengurangi penggunaan memori. Namun aliran ini tidak mendukung penempatan posisi dan properti Length. Jika Anda memerlukan fitur ini, silakan gunakan properti Contents sebagai gantinya.

**Returns:**
Objek InputStream

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Mendapatkan nama unicode spesifikasi file.

**Returns:**
nilai String

### getValue {#getValue-java.lang.String-}
Mendapatkan parameter khusus aplikasi.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Jika true, isi file akan disertakan dalam spesifikasi file.

**Returns:**
nilai boolean

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Hubungan file terkait.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Mengatur isi file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array byte |

### setContents {#setContents-java.io.InputStream-}
Mengatur isi file.

### setDescription {#setDescription-java.lang.String-}
Mengatur teks yang terkait dengan spesifikasi file.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Mengatur format enkoding. Nilai yang mungkin: Zip - file dikompresi dengan ZIP, None - file tidak dikompresi.

### setFileSystem {#setFileSystem-java.lang.String-}
Mengatur nama sistem file.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Jika true, isi file akan disertakan dalam spesifikasi file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMIMEType {#setMIMEType-java.lang.String-}
Mengatur MIMEType.

### setName {#setName-java.lang.String-}
Mengatur nama spesifikasi file.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Mengatur parameter file.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Mengatur nama unicode spesifikasi file.

### setValue {#setValue-java.lang.String-java.lang.String-}
Mengatur parameter khusus aplikasi.
