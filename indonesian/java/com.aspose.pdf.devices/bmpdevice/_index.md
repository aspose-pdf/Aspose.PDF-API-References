---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam format bmp."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam format bmp.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default. |
| [BmpDevice](#BmpDevice-int-int-) | Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan dimensi gambar yang diberikan, resolusi default (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | merender halaman pada grafik |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Mengonversi halaman menjadi bmp dan menyimpannya ke aliran output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Hanya untuk penggunaan internal! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan dimensi gambar yang diberikan, resolusi default (=150).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar output gambar. |
| tinggi |  | Tinggi output gambar. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code BmpDevice} dengan resolusi default.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
merender halaman pada grafik

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Mengonversi halaman menjadi bmp dan menyimpannya ke aliran output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Hanya untuk penggunaan internal!
