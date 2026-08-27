---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke png."
type: docs
weight: 160
url: /id/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke png.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PngDevice](#PngDevice--) | Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default. |
| [PngDevice](#PngDevice-int-int-) | Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan dimensi gambar yang diberikan, resolusi default (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Mendapatkan atau mengatur apakah gambar memiliki latar belakang transparan. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Mengonversi halaman menjadi png dan menyimpannya ke aliran output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Mengonversi halaman menjadi png dan menyimpannya ke aliran output. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Mengonversi halaman menjadi BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Mengonversi halaman menjadi BufferedImage dengan binarisasi Bradley. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Mendapatkan atau mengatur apakah gambar memiliki latar belakang transparan. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan dimensi gambar yang diberikan, resolusi default (=150).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar output gambar. |
| tinggi |  | Tinggi output gambar. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code PngDevice} dengan resolusi default.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Mendapatkan atau mengatur apakah gambar memiliki latar belakang transparan.

**Returns:**
nilai boolean

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Mengonversi halaman menjadi png dan menyimpannya ke aliran output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Mengonversi halaman menjadi png dan menyimpannya ke aliran output.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Mengonversi halaman menjadi BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Mengonversi halaman menjadi BufferedImage dengan binarisasi Bradley.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Mendapatkan atau mengatur apakah gambar memiliki latar belakang transparan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
