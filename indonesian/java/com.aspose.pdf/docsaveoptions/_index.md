---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format Doc"
type: docs
weight: 1030
url: /id/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opsi penyimpanan untuk ekspor ke format Doc

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Handler ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang diproses saat ini, contoh kode handler yang menampilkan kemajuan di konsol adalah : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Dapatkan format output |
| [getImageResolutionX](#getImageResolutionX--) | Resolusi X gambar yang dikonversi. |
| [getImageResolutionY](#getImageResolutionY--) | Resolusi Y gambar yang dikonversi. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf. Menentukan seberapa jauh jarak antara dua baris teks relatif. Ditentukan dalam ratusan persen dari tinggi baris teks. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan data sementara saat melakukan konversi dalam mode penyimpanan memori. |
| [getMode](#getMode--) | Mode pengenalan. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | Pada PDF, kata dapat direpresentasikan secara internal dengan operator yang mencetak kata dengan mencetak huruf atau suku kata secara terpisah. Jadi, untuk mendeteksi kata kadang-kadang kita perlu mendeteksi kelompok karakter independen yang sebenarnya merupakan kata. Pengaturan ini menentukan lebar spasi antara elemen teks (huruf, suku kata) yang harus diperlakukan sebagai jarak antar kata selama pengenalan kata dalam PDF sumber. (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti elemen teks tersebut termasuk kata yang berbeda). Nilainya dinormalkan terhadap ukuran font – 1,0 berarti 100% dari ukuran font kata yang dimaksud. PERHATIAN! Hanya digunakan ketika PDF sumber berisi font khusus yang jarang digunakan sehingga nilai optimal tidak dapat dihitung dari font. Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa pun pada dokumen hasil. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Digunakan untuk paragraf atau jeda baris. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Mendapatkan atau mengatur konversi untuk font Type3. Pada font Type 3, glif harus didefinisikan oleh aliran operator grafik. Ini berarti bahwa pada output DOC/DOCX kita melihat gambar alih-alih teks. Atur flag ini ke true untuk mengonversi font Type3 ke TTF dan mendapatkan teks dalam file hasil. |
| [isRecognizeBullets](#isRecognizeBullets--) | Aktifkan pengenalan bullet. |
| [isReSaveFonts](#isReSaveFonts--) | Mendapatkan atau mengatur prosedur untuk menyimpan ulang font. Jika diatur ke true, kami memuat ulang font pada setiap halaman untuk menghindari pengaruh properti font sebelumnya dan memuat font yang baru dibuat dari awal. Atur opsi ini ke false jika Anda ingin meningkatkan kinerja. Nilai default adalah true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Gunakan paragraf atau jeda baris |
| [setBatchSize](#setBatchSize-int-) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Mendapatkan atau mengatur konversi untuk font Type3. Pada font Type 3, glif harus didefinisikan oleh aliran operator grafik. Ini berarti bahwa pada output DOC/DOCX kita melihat gambar alih-alih teks. Atur flag ini ke true untuk mengonversi font Type3 ke TTF dan mendapatkan teks dalam file hasil. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Penangkap ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Atur format output |
| [setImageResolutionX](#setImageResolutionX-int-) | Resolusi X gambar yang dikonversi. |
| [setImageResolutionY](#setImageResolutionY-int-) | Resolusi Y gambar yang dikonversi. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf. Menentukan seberapa jauh jarak antara dua baris teks relatif. Ditentukan dalam ratusan persen dari tinggi baris teks. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan data sementara saat melakukan konversi dalam mode penyimpanan memori. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Mode pengenalan. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Aktifkan pengenalan bullet. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | Pada PDF, kata dapat direpresentasikan secara internal dengan operator yang mencetak kata dengan mencetak huruf atau suku kata secara terpisah. Jadi, untuk mendeteksi kata kadang-kadang kita perlu mendeteksi kelompok karakter independen yang sebenarnya merupakan kata. Pengaturan ini menentukan lebar spasi antara elemen teks (huruf, suku kata) yang harus diperlakukan sebagai jarak antar kata selama pengenalan kata dalam PDF sumber. (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti elemen teks tersebut termasuk kata yang berbeda). Nilainya dinormalkan terhadap ukuran font – 1,0 berarti 100% dari ukuran font kata yang dimaksud. PERHATIAN! Hanya digunakan ketika PDF sumber berisi font khusus yang jarang digunakan sehingga nilai optimal tidak dapat dihitung dari font. Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa pun pada dokumen hasil. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Mendapatkan atau mengatur prosedur untuk menyimpan ulang font. Jika diatur ke true, kami memuat ulang font pada setiap halaman untuk menghindari pengaruh properti font sebelumnya dan memuat font yang baru dibuat dari awal. Atur opsi ini ke false jika Anda ingin meningkatkan kinerja. Nilai default adalah true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Konstruktor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Returns:**
nilai int

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Penangan ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang diproses saat ini, contoh kode penangan yang menampilkan kemajuan di konsol adalah : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
instansi ConversionProgressEventHandler

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Dapatkan format output

**Returns:**
Elemen DocFormat @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Resolusi X gambar yang dikonversi.

**Returns:**
nilai int

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Resolusi Y gambar yang dikonversi.

**Returns:**
nilai int

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf. Menentukan seberapa jauh jarak antara dua baris teks relatif. Ditentukan dalam ratusan persen dari tinggi baris teks.

**Returns:**
nilai float

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan data sementara saat melakukan konversi dalam mode penyimpanan memori.

**Returns:**
nilai String

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Mode pengenalan.

**Returns:**
Nilai RecognitionMode @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

Pada PDF, kata dapat direpresentasikan secara internal dengan operator yang mencetak kata dengan mencetak huruf atau suku kata secara terpisah. Jadi, untuk mendeteksi kata kadang-kadang kita perlu mendeteksi kelompok karakter independen yang sebenarnya merupakan kata. Pengaturan ini menentukan lebar spasi antara elemen teks (huruf, suku kata) yang harus diperlakukan sebagai jarak antar kata selama pengenalan kata dalam PDF sumber. (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti elemen teks tersebut termasuk kata yang berbeda). Nilainya dinormalkan terhadap ukuran font – 1,0 berarti 100% dari ukuran font kata yang dimaksud. PERHATIAN! Hanya digunakan ketika PDF sumber berisi font khusus yang jarang digunakan sehingga nilai optimal tidak dapat dihitung dari font. Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa pun pada dokumen hasil.

**Returns:**
Kedekatan relatif

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Digunakan untuk paragraf atau jeda baris.

**Returns:**
nilai boolean.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Mendapatkan atau mengatur konversi untuk font Type3. Pada font Type 3, glif harus didefinisikan oleh aliran operator grafik. Ini berarti bahwa pada output DOC/DOCX kita melihat gambar alih-alih teks. Atur flag ini ke true untuk mengonversi font Type3 ke TTF dan mendapatkan teks dalam file hasil.

**Returns:**
nilai boolean

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Aktifkan pengenalan bullet.

**Returns:**
nilai boolean

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Mendapatkan atau mengatur prosedur untuk menyimpan ulang font. Jika diatur ke true, kami memuat ulang font pada setiap halaman untuk menghindari pengaruh properti font sebelumnya dan memuat font yang baru dibuat dari awal. Atur opsi ini ke false jika Anda ingin meningkatkan kinerja. Nilai default adalah true;

**Returns:**
nilai boolean

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Gunakan paragraf atau jeda baris

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Mendapatkan atau mengatur konversi untuk font Type3. Pada font Type 3, glif harus didefinisikan oleh aliran operator grafik. Ini berarti bahwa pada output DOC/DOCX kita melihat gambar alih-alih teks. Atur flag ini ke true untuk mengonversi font Type3 ke TTF dan mendapatkan teks dalam file hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Penangkap ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Atur format output

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Resolusi X gambar yang dikonversi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Resolusi Y gambar yang dikonversi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf. Menentukan seberapa jauh jarak antara dua baris teks relatif. Ditentukan dalam ratusan persen dari tinggi baris teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan data sementara saat melakukan konversi dalam mode penyimpanan memori.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Mode pengenalan.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Aktifkan pengenalan bullet.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

Pada PDF, kata dapat direpresentasikan secara internal dengan operator yang mencetak kata dengan mencetak huruf atau suku kata secara terpisah. Jadi, untuk mendeteksi kata kadang-kadang kita perlu mendeteksi kelompok karakter independen yang sebenarnya merupakan kata. Pengaturan ini menentukan lebar spasi antara elemen teks (huruf, suku kata) yang harus diperlakukan sebagai jarak antar kata selama pengenalan kata dalam PDF sumber. (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti elemen teks tersebut termasuk kata yang berbeda). Nilainya dinormalkan terhadap ukuran font – 1,0 berarti 100% dari ukuran font kata yang dimaksud. PERHATIAN! Hanya digunakan ketika PDF sumber berisi font khusus yang jarang digunakan sehingga nilai optimal tidak dapat dihitung dari font. Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa pun pada dokumen hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Kedekatan relatif |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Mendapatkan atau mengatur prosedur untuk menyimpan ulang font. Jika diatur ke true, kami memuat ulang font pada setiap halaman untuk menghindari pengaruh properti font sebelumnya dan memuat font yang baru dibuat dari awal. Atur opsi ini ke false jika Anda ingin meningkatkan kinerja. Nilai default adalah true;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
