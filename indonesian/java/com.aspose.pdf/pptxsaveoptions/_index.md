---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format SVG"
type: docs
weight: 3950
url: /id/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

Opsi penyimpanan untuk ekspor ke format SVG

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Penangan ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode penangan yang menampilkan kemajuan di konsol adalah: </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Mendapatkan atau mengatur resolusi gambar (dpi). Default adalah 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | Jika disetel ke true maka gambar dipisahkan dari semua grafik lainnya |
| [getSlidesAsImages](#getSlidesAsImages--) | Jika disetel ke true maka semua konten dikenali sebagai gambar (satu per halaman) |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Mengaktifkan atau menonaktifkan pengenalan kolom teks |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Penangkap ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya. |
| [setImageResolution](#setImageResolution-int-) | Mendapatkan atau mengatur resolusi gambar (dpi). Default adalah 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Mengaktifkan atau menonaktifkan pengenalan kolom teks |
| [setSeparateImages](#setSeparateImages-boolean-) | Jika disetel ke true maka gambar dipisahkan dari semua grafik lainnya |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Jika disetel ke true maka semua konten dikenali sebagai gambar (satu per halaman) |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Konstruktor

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Penangan ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode penangan yang menampilkan kemajuan di konsol adalah: </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
instansi ConversionProgressEventHandler

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Mendapatkan atau mengatur resolusi gambar (dpi). Default adalah 192 dpi.

**Returns:**
nilai int

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Jika disetel ke true maka gambar dipisahkan dari semua grafik lainnya

**Returns:**
nilai boolean

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Jika disetel ke true maka semua konten dikenali sebagai gambar (satu per halaman)

**Returns:**
nilai boolean

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Mengaktifkan atau menonaktifkan pengenalan kolom teks

**Returns:**
nilai boolean

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Penangkap ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Mendapatkan atau mengatur resolusi gambar (dpi). Default adalah 192 dpi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Mengaktifkan atau menonaktifkan pengenalan kolom teks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Jika disetel ke true maka gambar dipisahkan dari semua grafik lainnya

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Jika disetel ke true maka semua konten dikenali sebagai gambar (satu per halaman)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
