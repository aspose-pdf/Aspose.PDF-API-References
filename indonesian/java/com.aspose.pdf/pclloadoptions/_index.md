---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memuat (import) file PCL ke dalam dokumen pdf."
type: docs
weight: 3530
url: /id/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Mewakili opsi untuk memuat (import) file PCL ke dalam dokumen pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Membuat objek {@code PclLoadOptions}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [getConversionEngine](#getConversionEngine--) | Mendefinisikan mesin konversi yang akan digunakan untuk konversi |
| [getExceptions](#getExceptions--) | Daftar kesalahan konversi. |
| [isSupressErrors](#isSupressErrors--) | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah kesalahan konversi PCL harus ditekan. |
| [setBatchSize](#setBatchSize-int-) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [setConversionEngine](#setConversionEngine-int-) | Mendefinisikan mesin konversi yang akan digunakan untuk konversi |
| [setSupressErrors](#setSupressErrors-boolean-) | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah kesalahan konversi PCL harus ditekan. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Membuat objek {@code PclLoadOptions}.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Returns:**
nilai int

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Mendefinisikan mesin konversi yang akan digunakan untuk konversi

**Returns:**
Elemen ConversionEngines @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Daftar kesalahan konversi.

**Returns:**
Daftar Pengecualian

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah kesalahan konversi PCL harus ditekan.

**Returns:**
nilai boolean

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Mendefinisikan mesin konversi yang akan digunakan untuk konversi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| conversionEngine |  | Elemen ConversionEngines @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah kesalahan konversi PCL harus ditekan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| supressErrors |  | nilai boolean |
