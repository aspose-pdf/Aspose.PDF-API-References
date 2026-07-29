---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini membantu menyimpan halaman dokumen pdf satu per satu ke dalam satu gambar tiff."
type: docs
weight: 210
url: /id/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Kelas ini membantu menyimpan halaman dokumen pdf satu per satu ke dalam satu gambar tiff.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-int-int-) | Menginisialisasi instance baru dari kelas {@code TiffDevice}. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Lakukan binarisasi Bradley untuk aliran masukan. |
| [getCropRectangle](#getCropRectangle--) | Dapatkan persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar. Nilai default adalah null, dalam hal ini seluruh gambar dikonversi menjadi halaman. |
| [getFormPresentationMode](#getFormPresentationMode--) | Mendapatkan mode presentasi formulir. |
| [getHeight](#getHeight--) | Mendapatkan tinggi output gambar. |
| [getRenderingOptions](#getRenderingOptions--) | Mendapatkan opsi rendering. |
| [getResolution](#getResolution--) | Mendapatkan resolusi gambar. |
| [getSettings](#getSettings--) | Mendapatkan pengaturan untuk memetakan pdf ke gambar tiff. |
| [getWidth](#getWidth--) | Mendapatkan lebar output gambar. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Mengonversi halaman dokumen tertentu menjadi tiff dan menyimpannya dalam aliran output. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Mengonversi halaman dokumen tertentu menjadi tiff dan menyimpannya dalam aliran output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Melakukan beberapa operasi pada halaman yang diberikan, misalnya. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Atur persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Mendapatkan mode presentasi formulir. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Mengatur opsi rendering. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Menginisialisasi instance baru dari kelas {@code TiffDevice}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar output gambar. |
| tinggi |  | Tinggi output gambar. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Menginisialisasi instance baru dari kelas {@code TiffDevice} dengan pengaturan default.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Lakukan binarisasi Bradley untuk aliran masukan.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Dapatkan persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar. Nilai default adalah null, dalam hal ini seluruh gambar dikonversi menjadi halaman.

**Returns:**
objek Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Mendapatkan mode presentasi formulir.

**Returns:**
Nilai FormPresentationMode @see FormPresentationMode

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
opsi rendering.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Mendapatkan resolusi gambar.

**Returns:**
Elemen Resolusi

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Mendapatkan pengaturan untuk memetakan pdf ke gambar tiff.

**Returns:**
Elemen TiffSettings

### getWidth {#getWidth--}
```
public int getWidth()
```

Mendapatkan lebar output gambar.

**Returns:**
nilai int

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Mengonversi halaman dokumen tertentu menjadi tiff dan menyimpannya dalam aliran output.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Mengonversi halaman dokumen tertentu menjadi tiff dan menyimpannya dalam aliran output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Melakukan beberapa operasi pada halaman yang diberikan, misalnya.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Atur persegi panjang yang mendefinisikan area yang akan dikonversi menjadi gambar.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Mendapatkan mode presentasi formulir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Mengatur opsi rendering.
