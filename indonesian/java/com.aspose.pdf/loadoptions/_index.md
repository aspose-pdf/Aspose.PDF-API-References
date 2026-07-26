---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Tipe LoadOptions menyimpan tingkat abstraksi pada opsi muat individu."
type: docs
weight: 2790
url: /id/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

Tipe LoadOptions menyimpan tingkat abstraksi pada opsi muat individu.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Mewakili format file yang dijelaskan oleh {@code LoadOptions}. |
| [getWarningHandler](#getWarningHandler--) | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Mendapatkan atau mengatur flag untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika {@code }, memungkinkan mengeksekusi operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam dokumen PDF meskipun aturan lisensi melarang penyematan untuk font ini. Secara default {@code }. Hati-hati saat menggunakan flag ini. Ketika diatur, berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum atas dirinya sendiri. Jadi ia melakukannya dengan risiko sendiri. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hukum hak cipta. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Mendapatkan atau mengatur flag untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika {@code }, memungkinkan mengeksekusi operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam dokumen PDF meskipun aturan lisensi melarang penyematan untuk font ini. Secara default {@code }. Hati-hati saat menggunakan flag ini. Ketika diatur, berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum atas dirinya sendiri. Jadi ia melakukannya dengan risiko sendiri. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hukum hak cipta. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Mewakili format file yang dijelaskan oleh {@code LoadOptions}.

**Returns:**
elemen LoadFormat @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti.

**Returns:**
Nilai IWarningCallback

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Mendapatkan atau mengatur flag untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika {@code }, memungkinkan mengeksekusi operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam dokumen PDF meskipun aturan lisensi melarang penyematan untuk font ini. Secara default {@code }. Hati-hati saat menggunakan flag ini. Ketika diatur, berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum atas dirinya sendiri. Jadi ia melakukannya dengan risiko sendiri. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hukum hak cipta.

**Returns:**
nilai boolean

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Mendapatkan atau mengatur flag untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika {@code }, memungkinkan mengeksekusi operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam dokumen PDF meskipun aturan lisensi melarang penyematan untuk font ini. Secara default {@code }. Hati-hati saat menggunakan flag ini. Ketika diatur, berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum atas dirinya sendiri. Jadi ia melakukannya dengan risiko sendiri. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hukum hak cipta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti.
