---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "TeX dosyasını PDF belgesine yükleme/ithal etme seçeneklerini temsil eder."
type: docs
weight: 4870
url: /tr/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

TeX dosyasını PDF belgesine yükleme/ithal etme seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | TeX dosyasını PDF belgesine dönüştürmek için varsayılan yükleme seçenekleri oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDateTime](#getDateTime--) | Yıl, ay, gün ve zaman gibi tarih/saat temel değerleri için belirli bir değeri alır/ayarlar. |
| [getInputDirectory](#getInputDirectory--) | TeX giriş dizinini alır/ayarlar. |
| [getJobName](#getJobName--) | İşin adını alır/ayarlar. |
| [getLoadResult](#getLoadResult--) | TeX yükleme ve derleme sonucu alır - her şey sorunsuz mu geçti yoksa yorum/hatalar var mı. |
| [getNoLigatures](#getNoLigatures--) | Tüm yazı tiplerindeki ligatürleri iptal eden bir bayrağı alır/ayarlar. |
| [getOutputDirectory](#getOutputDirectory--) | TeX çıktı dizinini alır/ayarlar. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Matematik formüllerini rasterleştirmeye izin veren bir bayrağı alır/ayarlar. |
| [getRepeat](#getRepeat--) | Giriş TeX dosyasında (dosyalarında) referanslar olduğu gibi durumlarda TeX işinin iki kez çalıştırılması gerekip gerekmediğini gösteren bayrağı alır/ayarlar. Genel olarak, bu davranış motorun dizgi süreci boyunca bazı verileri toplaması ve bunları ilk çalıştırmada yardımcı bir dosyada saklaması gerektiğinde faydalıdır. Ve ikinci çalıştırmada motor bu verileri bir şekilde kullanır. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | TeX'in gerektirdiği giriş dizinini alır/ayarlar. Gerekli giriş, ana .tex dosyasına bir şekilde dahil edilen dosyalardır; örneğin, yerleşik destek bulunmayan paketler. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Konsolda terminal çıktısının gösterilip gösterilmeyeceğini belirten bayrağı alır/ayarlar. |
| [getSubsetFonts](#getSubsetFonts--) | Alır/ayarlar, çıktı dosyasında yazı tiplerini alt kümeleyip alt kümelemeyeceğini belirten bayrağı. |
| [setDateTime](#setDateTime-java.util.Date-) | Yıl, ay, gün ve zaman gibi tarih/saat temel değerleri için belirli bir değeri alır/ayarlar. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | TeX giriş dizinini alır/ayarlar. |
| [setJobName](#setJobName-java.lang.String-) | İşin adını alır/ayarlar. |
| [setNoLigatures](#setNoLigatures-boolean-) | Tüm yazı tiplerindeki ligatürleri iptal eden bir bayrağı alır/ayarlar. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | TeX çıktı dizinini alır/ayarlar. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Matematik formüllerini rasterleştirmeye izin veren bir bayrağı alır/ayarlar. |
| [setRepeat](#setRepeat-boolean-) | Giriş TeX dosyasında (dosyalarında) referanslar olduğu gibi durumlarda TeX işinin iki kez çalıştırılması gerekip gerekmediğini gösteren bayrağı alır/ayarlar. Genel olarak, bu davranış motorun dizgi süreci boyunca bazı verileri toplaması ve bunları ilk çalıştırmada yardımcı bir dosyada saklaması gerektiğinde faydalıdır. Ve ikinci çalıştırmada motor bu verileri bir şekilde kullanır. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | TeX'in gerektirdiği giriş dizinini alır/ayarlar. Gerekli giriş, ana .tex dosyasına bir şekilde dahil edilen dosyalardır; örneğin, yerleşik destek bulunmayan paketler. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Konsolda terminal çıktısının gösterilip gösterilmeyeceğini belirten bayrağı alır/ayarlar. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Alır/ayarlar, çıktı dosyasında yazı tiplerini alt kümeleyip alt kümelemeyeceğini belirten bayrağı. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

TeX dosyasını PDF belgesine dönüştürmek için varsayılan yükleme seçenekleri oluşturur.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Yıl, ay, gün ve zaman gibi tarih/saat temel değerleri için belirli bir değeri alır/ayarlar.

**Returns:**
Date örneği

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

TeX giriş dizinini alır/ayarlar.

**Returns:**
ITeXInputDirectory örneği

### getJobName {#getJobName--}
```
public final String getJobName()
```

İşin adını alır/ayarlar.

**Returns:**
String değeri

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

TeX yükleme ve derleme sonucu alır - her şey sorunsuz mu geçti yoksa yorum/hatalar var mı.

**Returns:**
TeXLoadResult öğesi

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Tüm yazı tiplerindeki ligatürleri iptal eden bir bayrağı alır/ayarlar.

**Returns:**
boolean değer

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

TeX çıktı dizinini alır/ayarlar.

**Returns:**
ITeXOutputDirectory örneği

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Matematik formüllerini rasterleştirmeye izin veren bir bayrağı alır/ayarlar.

**Returns:**
boolean değer

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Giriş TeX dosyasında (dosyalarında) referanslar olduğu gibi durumlarda TeX işinin iki kez çalıştırılması gerekip gerekmediğini gösteren bayrağı alır/ayarlar. Genel olarak, bu davranış motorun dizgi süreci boyunca bazı verileri toplaması ve bunları ilk çalıştırmada yardımcı bir dosyada saklaması gerektiğinde faydalıdır. Ve ikinci çalıştırmada motor bu verileri bir şekilde kullanır.

**Returns:**
boolean değer

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

TeX'in gerektirdiği giriş dizinini alır/ayarlar. Gerekli giriş, ana .tex dosyasına bir şekilde dahil edilen dosyalardır; örneğin, yerleşik destek bulunmayan paketler.

**Returns:**
ITeXInputDirectory örneği

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Konsolda terminal çıktısının gösterilip gösterilmeyeceğini belirten bayrağı alır/ayarlar.

**Returns:**
boolean değer

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Alır/ayarlar, çıktı dosyasında yazı tiplerini alt kümeleyip alt kümelemeyeceğini belirten bayrağı.

**Returns:**
boolean değer

### setDateTime {#setDateTime-java.util.Date-}
Yıl, ay, gün ve zaman gibi tarih/saat temel değerleri için belirli bir değeri alır/ayarlar.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
TeX giriş dizinini alır/ayarlar.

### setJobName {#setJobName-java.lang.String-}
İşin adını alır/ayarlar.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Tüm yazı tiplerindeki ligatürleri iptal eden bir bayrağı alır/ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
TeX çıktı dizinini alır/ayarlar.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Matematik formüllerini rasterleştirmeye izin veren bir bayrağı alır/ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Giriş TeX dosyasında (dosyalarında) referanslar olduğu gibi durumlarda TeX işinin iki kez çalıştırılması gerekip gerekmediğini gösteren bayrağı alır/ayarlar. Genel olarak, bu davranış motorun dizgi süreci boyunca bazı verileri toplaması ve bunları ilk çalıştırmada yardımcı bir dosyada saklaması gerektiğinde faydalıdır. Ve ikinci çalıştırmada motor bu verileri bir şekilde kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
TeX'in gerektirdiği giriş dizinini alır/ayarlar. Gerekli giriş, ana .tex dosyasına bir şekilde dahil edilen dosyalardır; örneğin, yerleşik destek bulunmayan paketler.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Konsolda terminal çıktısının gösterilip gösterilmeyeceğini belirten bayrağı alır/ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Alır/ayarlar, çıktı dosyasında yazı tiplerini alt kümeleyip alt kümelemeyeceğini belirten bayrağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
