---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini mewakili pengaturan untuk mengimpor pdf ke Tiff."
type: docs
weight: 220
url: /id/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Kelas ini mewakili pengaturan untuk mengimpor pdf ke Tiff.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBrightness](#getBrightness--) | Dapatkan batas nilai transformasi warna antara putih dan hitam. Parameter ini dapat diterapkan dengan EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle atau ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Mendapatkan tipe kompresi. </p> Value: Tipe kompresi. <hr> <p> Nilai default adalah CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [getDepth](#getDepth--) | <p> Mendapatkan kedalaman warna. </p> Value: Kedalaman warna. <hr> <p> Nilai default adalah ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Mendapatkan IndexedConversionType. Nilai default adalah Simple. |
| [getMargins](#getMargins--) | Mendapatkan margin. |
| [getShape](#getShape--) | <p> Mendapatkan tipe bentuk. </p> Value: Tipe bentuk. <hr> <p> Nilai default adalah ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Mendapatkan nilai yang menunjukkan apakah harus melewatkan halaman kosong. </p> Value: {@code true} jika perlu melewatkan halaman kosong; jika tidak, {@code false}. <hr> <p> Nilai default adalah false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Mendapatkan flag yang menentukan apakah mesin imaging alternatif digunakan atau tidak. Nilai true digunakan secara default untuk Linux OS. Untuk Windows OS nilai default adalah false. |
| [setBrightness](#setBrightness-float-) | Setel batas nilai transformasi warna antara putih dan hitam. Parameter ini dapat diterapkan dengan EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle atau ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Mengatur tipe kompresi. </p> Value: Tipe kompresi. <hr> <p> Nilai default adalah CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Mendapatkan kedalaman warna. </p> Value: Kedalaman warna. <hr> <p> Nilai default adalah ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Mengatur IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Mengatur tipe bentuk. </p> Value: Tipe bentuk. <hr> <p> Nilai default adalah ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Mengatur nilai yang menunjukkan apakah akan melewatkan halaman kosong. </p> Value: {@code true} jika perlu melewatkan halaman kosong; jika tidak, {@code false}. <hr> <p> Nilai default adalah false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Mengatur sebuah flag yang menentukan apakah mesin imaging alternatif digunakan atau tidak. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| skipBlankPages |  | jika diatur ke {@code true} [lewatkan halaman kosong]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Menginisialisasi sebuah instance baru dari kelas {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Dapatkan batas nilai transformasi warna antara putih dan hitam. Parameter ini dapat diterapkan dengan EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle atau ColorDepth.Format1bpp == 1

**Returns:**
nilai float kecerahan harus berada dalam rentang 0 hingga 1. Secara default nilai adalah 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Mendapatkan tipe kompresi. </p> Value: Tipe kompresi. <hr> <p> Nilai default adalah CompressionType.LZW </p>

**Returns:**
elemen CompressionType @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

**Returns:**
nilai PageCoordinateType @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Mendapatkan kedalaman warna. </p> Value: Kedalaman warna. <hr> <p> Nilai default adalah ColorDepth.Default </p>

**Returns:**
elemen ColorDepth @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Mendapatkan IndexedConversionType. Nilai default adalah Simple.

**Returns:**
elemen IndexedConversionType @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Mendapatkan margin.

**Returns:**
objek Margins

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Mendapatkan tipe bentuk. </p> Value: Tipe bentuk. <hr> <p> Nilai default adalah ShapeType.None </p>

**Returns:**
elemen ShapeType @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Mendapatkan nilai yang menunjukkan apakah harus melewatkan halaman kosong. </p> Value: {@code true} jika perlu melewatkan halaman kosong; jika tidak, {@code false}. <hr> <p> Nilai default adalah false </p>

**Returns:**
nilai boolean

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Mendapatkan flag yang menentukan apakah mesin imaging alternatif digunakan atau tidak. Nilai true digunakan secara default untuk Linux OS. Untuk Windows OS nilai default adalah false.

**Returns:**
nilai boolean

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Setel batas nilai transformasi warna antara putih dan hitam. Parameter ini dapat diterapkan dengan EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle atau ColorDepth.Format1bpp == 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | : Nilai kecerahan harus berada dalam rentang 0 hingga 1. Secara default nilai adalah 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Mengatur tipe kompresi. </p> Value: Tipe kompresi. <hr> <p> Nilai default adalah CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Mendapatkan kedalaman warna. </p> Value: Kedalaman warna. <hr> <p> Nilai default adalah ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Mengatur IndexedConversionType.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen IndexedConversionType @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Mengatur tipe bentuk. </p> Value: Tipe bentuk. <hr> <p> Nilai default adalah ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Mengatur nilai yang menunjukkan apakah akan melewatkan halaman kosong. </p> Value: {@code true} jika perlu melewatkan halaman kosong; jika tidak, {@code false}. <hr> <p> Nilai default adalah false </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Mengatur sebuah flag yang menentukan apakah mesin imaging alternatif digunakan atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| useAlternativeImageEngine |  | nilai boolean |
