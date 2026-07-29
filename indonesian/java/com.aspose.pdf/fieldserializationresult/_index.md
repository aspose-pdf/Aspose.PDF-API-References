---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili hasil proses serialisasi bidang formulir."
type: docs
weight: 1390
url: /id/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Mewakili hasil proses serialisasi bidang formulir.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Menginisialisasi instance baru dari kelas {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Menginisialisasi instance baru dari kelas {@link FieldSerializationResult}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Mendapatkan pesan kesalahan yang terkait dengan proses serialisasi. Nilai: Sekumpulan pesan kesalahan. |
| [getFieldFullName](#getFieldFullName--) | Mendapatkan nama lengkap bidang. Nilai: Nama lengkap bidang. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Mendapatkan status serialisasi bidang formulir. Nilai: Status serialisasi bidang formulir. |
| [getWarningMessages](#getWarningMessages--) | Mendapatkan pesan peringatan yang terkait dengan proses serialisasi. Nilai: Sekumpulan pesan peringatan. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Memperbarui status serialisasi dan menambahkan pesan ke set yang sesuai. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Menginisialisasi instance baru dari kelas {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Menginisialisasi instance baru dari kelas {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Mendapatkan pesan kesalahan yang terkait dengan proses serialisasi. Nilai: Sekumpulan pesan kesalahan.

**Returns:**
Instansi HashSet dari String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Mendapatkan nama lengkap bidang. Nilai: Nama lengkap bidang.

**Returns:**
nilai String

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Mendapatkan status serialisasi bidang formulir. Nilai: Status serialisasi bidang formulir.

**Returns:**
Elemen FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Mendapatkan pesan peringatan yang terkait dengan proses serialisasi. Nilai: Sekumpulan pesan peringatan.

**Returns:**
Instansi HashSet dari String

### updateStatus {#updateStatus-int-java.lang.String-}
Memperbarui status serialisasi dan menambahkan pesan ke set yang sesuai.
