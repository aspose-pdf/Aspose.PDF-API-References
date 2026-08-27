---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format Excel"
type: docs
weight: 1260
url: /id/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Opsi penyimpanan untuk ekspor ke format Excel

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Mendapatkan atau mengatur faktor yang akan diterapkan pada ukuran font skala (virtual) selama konversi ke tabel Excel dalam / * mesin legacy. Penetapan nilai yang lebih kecil memudahkan pencarian kolom dan mencegah penggabungan mereka untuk beberapa / * dokumen. Nilai default adalah 0.9; Menetapkan nilai ke nol memungkinkan algoritma memilih skala secara otomatis. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Atur menjadi true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; artinya setiap halaman PDF disimpan sebagai lembar kerja terpisah. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Set false jika Anda perlu menekan penyisipan kolom kosong sebagai kolom pertama pada lembar kerja. Nilai default adalah true; artinya kolom kosong akan disisipkan. |
| [isUniformWorksheets](#isUniformWorksheets--) | Set true untuk menggunakan pembagian kolom seragam di seluruh dokumen. Nilai default adalah false; artinya pembagian kolom akan independen untuk setiap halaman. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Format output |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Set false jika Anda perlu menekan penyisipan kolom kosong sebagai kolom pertama pada lembar kerja. Nilai default adalah true; artinya kolom kosong akan disisipkan. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Atur menjadi true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; artinya setiap halaman PDF disimpan sebagai lembar kerja terpisah. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Mendefinisikan mesin konversi yang akan digunakan untuk konversi |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Konstruktor

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Mendapatkan atau mengatur faktor yang akan diterapkan pada ukuran font skala (virtual) selama konversi ke tabel Excel dalam / * mesin legacy. Penetapan nilai yang lebih kecil memudahkan pencarian kolom dan mencegah penggabungan mereka untuk beberapa / * dokumen. Nilai default adalah 0.9; Menetapkan nilai ke nol memungkinkan algoritma memilih skala secara otomatis. / * / * / *

**Returns:**
nilai double /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Atur menjadi true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; artinya setiap halaman PDF disimpan sebagai lembar kerja terpisah.

**Returns:**
nilai boolean

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Set false jika Anda perlu menekan penyisipan kolom kosong sebagai kolom pertama pada lembar kerja. Nilai default adalah true; artinya kolom kosong akan disisipkan.

**Returns:**
nilai boolean

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Set true untuk menggunakan pembagian kolom seragam di seluruh dokumen. Nilai default adalah false; artinya pembagian kolom akan independen untuk setiap halaman.

**Returns:**
nilai boolean

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Format output

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Set false jika Anda perlu menekan penyisipan kolom kosong sebagai kolom pertama pada lembar kerja. Nilai default adalah true; artinya kolom kosong akan disisipkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Atur menjadi true jika Anda perlu meminimalkan jumlah lembar kerja dalam buku kerja yang dihasilkan. Nilai default adalah false; artinya setiap halaman PDF disimpan sebagai lembar kerja terpisah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Mendefinisikan mesin konversi yang akan digunakan untuk konversi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |
