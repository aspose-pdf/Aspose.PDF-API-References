---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke jpeg."
type: docs
weight: 130
url: /id/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke jpeg.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-int-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice}. |
| [JpegDevice](#JpegDevice-int-int-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan dimensi gambar yang diberikan, resolusi default (=150), dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Mengonversi halaman menjadi jpeg dan menyimpannya ke dalam aliran output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Mengonversi halaman menjadi jpeg dan menyimpannya ke dalam aliran output. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kualitas |  | Menentukan tingkat kompresi untuk sebuah gambar. Rentang nilai yang berguna untuk kualitas adalah dari 0 hingga 100. Semakin rendah angka yang ditentukan, semakin tinggi kompresi dan oleh karena itu kualitas gambar semakin rendah. Nilai 0 akan memberikan gambar dengan kualitas terendah dan 100 yang tertinggi. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan dimensi gambar yang diberikan, resolusi default (=150), dan kualitas maksimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar output gambar. |
| tinggi |  | Tinggi output gambar. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Menginisialisasi sebuah instance baru dari kelas {@code JpegDevice} dengan resolusi default dan kualitas maksimum.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Mengonversi halaman menjadi jpeg dan menyimpannya ke dalam aliran output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Mengonversi halaman menjadi jpeg dan menyimpannya ke dalam aliran output.
