---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar opsi untuk mengekspor bidang formulir."
type: docs
weight: 1310
url: /id/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Mewakili kelas dasar opsi untuk mengekspor bidang formulir.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah nilai password harus diekspor. Nilai: {@code true} jika nilai password harus diekspor; jika tidak, {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Mendapatkan delegasi yang menentukan apakah suatu bidang tertentu harus diekspor. Jika delegasi {@code null}, semua bidang akan diekspor (perilaku default). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah nilai password harus diekspor. Nilai: {@code true} jika nilai password harus diekspor; jika tidak, {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Mengatur delegasi yang menentukan apakah suatu bidang tertentu harus diekspor. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah nilai password harus diekspor. Nilai: {@code true} jika nilai password harus diekspor; jika tidak, {@code false}.

**Returns:**
nilai boolean

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Mendapatkan delegasi yang menentukan apakah suatu bidang tertentu harus diekspor. Jika delegasi {@code null}, semua bidang akan diekspor (perilaku default).

**Returns:**
sebuah delegasi yang menentukan apakah suatu bidang tertentu harus diekspor.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah nilai password harus diekspor. Nilai: {@code true} jika nilai password harus diekspor; jika tidak, {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Mengatur delegasi yang menentukan apakah suatu bidang tertentu harus diekspor.
