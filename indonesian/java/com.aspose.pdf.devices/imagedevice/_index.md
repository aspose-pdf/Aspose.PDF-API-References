---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas abstrak untuk perangkat gambar."
type: docs
weight: 110
url: /id/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Kelas abstrak untuk perangkat gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan dimensi gambar yang diberikan dan resolusi default (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Mengonversi halaman menjadi {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [getCropRectangle](#getCropRectangle--) | Dapatkan persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar. Nilai default adalah null, dalam hal ini seluruh halaman akan dikonversi menjadi gambar. |
| [getFormPresentationMode](#getFormPresentationMode--) | Mendapatkan mode presentasi formulir. |
| [getHeight](#getHeight--) | Mendapatkan tinggi output gambar. |
| [getRenderingOptions](#getRenderingOptions--) | Mendapatkan opsi rendering. |
| [getResolution](#getResolution--) | Mendapatkan resolusi gambar. |
| [getWidth](#getWidth--) | Mendapatkan lebar output gambar. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Apakah kinerja proses shading tinggi. Secara default bernilai true. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Atur persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Mengatur mode presentasi formulir. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Mengatur opsi rendering. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Mengatur apakah kinerja proses shading tinggi atau tidak. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan dimensi gambar yang diberikan dan resolusi default (=150).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar output gambar. |
| tinggi |  | Tinggi output gambar. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Inisialisasi abstrak untuk turunan {@code ImageDevice}, atur resolusi menjadi 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Mengonversi halaman menjadi {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

**Returns:**
Elemen PageCoordinateType @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Dapatkan persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar. Nilai default adalah null, dalam hal ini seluruh halaman akan dikonversi menjadi gambar.

**Returns:**
objek Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Mendapatkan mode presentasi formulir.

**Returns:**
Elemen FormPresentationMode @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Mendapatkan tinggi output gambar.

**Returns:**
nilai int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Mendapatkan opsi rendering.

**Returns:**
Elemen RenderingOptions

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Mendapatkan resolusi gambar.

**Returns:**
Elemen Resolusi

### getWidth {#getWidth--}
```
public int getWidth()
```

Mendapatkan lebar output gambar.

**Returns:**
nilai int

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Apakah kinerja proses shading tinggi. Secara default bernilai true.

**Returns:**
nilai boolean

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Atur persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Mengatur mode presentasi formulir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen FormPresentationMode @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Mengatur opsi rendering.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Mengatur apakah kinerja proses shading tinggi atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
