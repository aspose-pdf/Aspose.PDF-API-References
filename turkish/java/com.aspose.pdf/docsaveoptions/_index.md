---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Doc formatına dışa aktarma için kaydetme seçenekleri."
type: docs
weight: 1030
url: /tr/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Doc formatına dışa aktarma için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir; örneğin işlenmiş sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir, konsolda ilerlemeyi gösteren işleyicinin kod örneği şu şekildedir: </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Çıktı formatını al |
| [getImageResolutionX](#getImageResolutionX--) | Dönüştürülen görüntülerin X çözünürlüğü. |
| [getImageResolutionY](#getImageResolutionY--) | Dönüştürülen görüntülerin Y çözünürlüğü. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Bu parametre, metin satırlarını paragraflara gruplamak için kullanılır. İki göreceli metin satırının ne kadar uzakta olabileceğini belirler. Metin satırının yüksekliğinin yüzde yüzler içinde belirtilir. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Bellek içinde kaydetme modunda dönüştürürken geçici verileri tutacak yolu (dosya adı veya dizin adı) tanımlar. |
| [getMode](#getMode--) | Tanıma modu. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | Pdf'de kelimeler, harflerini veya hecelerini bağımsız olarak yazdıran operatörlerle içsel olarak temsil edilebilir. Bu nedenle, kelimeleri tespit etmek için bazen aslında kelime olan bağımsız karakter gruplarını algılamamız gerekir. Bu ayar, kaynak PDF'deki kelimelerin tanınması sırasında kelimeler arasındaki mesafe olarak kabul edilmesi gereken metin öğeleri (harfler, heceler) arasındaki boşluk genişliğini tanımlar. (Harflar arasındaki en az bu genişlikteki boşluk, metin öğelerinin farklı kelimelere ait olduğunu gösterir). Font boyutuna göre normlanmıştır – 1.0, varsayılan kelime font boyutunun %100'ü anlamına gelir. DİKKAT! Bu yalnızca kaynak PDF, optimal değerin fonttan hesaplanamadığı nadir kullanılan belirli fontları içerdiğinde kullanılır. Dolayısıyla, çoğu durumda bu parametre sonuç belgesinde hiçbir değişiklik yapmaz. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Paragraf veya satır sonları kullanılır. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Type3 fontları için dönüşümü alır veya ayarlar. Type 3 fontlarda, glifler grafik operatör akışlarıyla tanımlanır. Bu, DOC/DOCX çıktısında metin yerine görüntüler gördüğümüz anlamına gelir. Bu bayrağı true olarak ayarlayın, Type3 fontları TTF'ye dönüştürmek ve sonuç dosyasında metin elde etmek için. |
| [isRecognizeBullets](#isRecognizeBullets--) | Madde işareti tanımını etkinleştir. |
| [isReSaveFonts](#isReSaveFonts--) | Fontların yeniden kaydedilme prosedürünü alır veya ayarlar. True olarak ayarlanırsa, önceki font özelliklerinin etkisini önlemek için her sayfada fontları yeniden yükler ve yeni oluşturulan fontu baştan yükler. Performansı artırmak istiyorsanız bu seçeneği false olarak ayarlayın. Varsayılan değer true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Paragraf veya satır sonlarını kullan |
| [setBatchSize](#setBatchSize-int-) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Type3 fontları için dönüşümü alır veya ayarlar. Type 3 fontlarda, glifler grafik operatör akışlarıyla tanımlanır. Bu, DOC/DOCX çıktısında metin yerine görüntüler gördüğümüz anlamına gelir. Bu bayrağı true olarak ayarlayın, Type3 fontları TTF'ye dönüştürmek ve sonuç dosyasında metin elde etmek için. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir, örn. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Çıktı formatını ayarla |
| [setImageResolutionX](#setImageResolutionX-int-) | Dönüştürülen görüntülerin X çözünürlüğü. |
| [setImageResolutionY](#setImageResolutionY-int-) | Dönüştürülen görüntülerin Y çözünürlüğü. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Bu parametre, metin satırlarını paragraflara gruplamak için kullanılır. İki göreceli metin satırının ne kadar uzakta olabileceğini belirler. Metin satırının yüksekliğinin yüzde yüzler içinde belirtilir. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Bellek içinde kaydetme modunda dönüştürürken geçici verileri tutacak yolu (dosya adı veya dizin adı) tanımlar. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Tanıma modu. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Madde işareti tanımını etkinleştir. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | Pdf'de kelimeler, harflerini veya hecelerini bağımsız olarak yazdıran operatörlerle içsel olarak temsil edilebilir. Bu nedenle, kelimeleri tespit etmek için bazen aslında kelime olan bağımsız karakter gruplarını algılamamız gerekir. Bu ayar, kaynak PDF'deki kelimelerin tanınması sırasında kelimeler arasındaki mesafe olarak kabul edilmesi gereken metin öğeleri (harfler, heceler) arasındaki boşluk genişliğini tanımlar. (Harflar arasındaki en az bu genişlikteki boşluk, metin öğelerinin farklı kelimelere ait olduğunu gösterir). Font boyutuna göre normlanmıştır – 1.0, varsayılan kelime font boyutunun %100'ü anlamına gelir. DİKKAT! Bu yalnızca kaynak PDF, optimal değerin fonttan hesaplanamadığı nadir kullanılan belirli fontları içerdiğinde kullanılır. Dolayısıyla, çoğu durumda bu parametre sonuç belgesinde hiçbir değişiklik yapmaz. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Fontların yeniden kaydedilme prosedürünü alır veya ayarlar. True olarak ayarlanırsa, önceki font özelliklerinin etkisini önlemek için her sayfada fontları yeniden yükler ve yeni oluşturulan fontu baştan yükler. Performansı artırmak istiyorsanız bu seçeneği false olarak ayarlayın. Varsayılan değer true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Yapıcı

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Returns:**
int değer

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir; örneğin işlenen sayfa sayısı hakkında ilerleme çubuğu veya mesajları göstermek için kullanılabilir. Konsolda ilerlemeyi gösteren işleyicinin kod örneği: </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler örneği

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Çıktı formatını al

**Returns:**
DocFormat öğesi @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Dönüştürülen görüntülerin X çözünürlüğü.

**Returns:**
int değer

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Dönüştürülen görüntülerin Y çözünürlüğü.

**Returns:**
int değer

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Bu parametre, metin satırlarını paragraflara gruplamak için kullanılır. İki göreceli metin satırının ne kadar uzakta olabileceğini belirler. Metin satırının yüksekliğinin yüzde yüzler içinde belirtilir.

**Returns:**
float değer

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Bellek içinde kaydetme modunda dönüştürürken geçici verileri tutacak yolu (dosya adı veya dizin adı) tanımlar.

**Returns:**
String değeri

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Tanıma modu.

**Returns:**
RecognitionMode değeri @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

Pdf'de kelimeler, harflerini veya hecelerini bağımsız olarak yazdıran operatörlerle içsel olarak temsil edilebilir. Bu nedenle, kelimeleri tespit etmek için bazen aslında kelime olan bağımsız karakter gruplarını algılamamız gerekir. Bu ayar, kaynak PDF'deki kelimelerin tanınması sırasında kelimeler arasındaki mesafe olarak kabul edilmesi gereken metin öğeleri (harfler, heceler) arasındaki boşluk genişliğini tanımlar. (Harflar arasındaki en az bu genişlikteki boşluk, metin öğelerinin farklı kelimelere ait olduğunu gösterir). Font boyutuna göre normlanmıştır – 1.0, varsayılan kelime font boyutunun %100'ü anlamına gelir. DİKKAT! Bu yalnızca kaynak PDF, optimal değerin fonttan hesaplanamadığı nadir kullanılan belirli fontları içerdiğinde kullanılır. Dolayısıyla, çoğu durumda bu parametre sonuç belgesinde hiçbir değişiklik yapmaz.

**Returns:**
Göreceli yakınlık

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Paragraf veya satır sonları kullanılır.

**Returns:**
boolean değer.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Type3 fontları için dönüşümü alır veya ayarlar. Type 3 fontlarda, glifler grafik operatör akışlarıyla tanımlanır. Bu, DOC/DOCX çıktısında metin yerine görüntüler gördüğümüz anlamına gelir. Bu bayrağı true olarak ayarlayın, Type3 fontları TTF'ye dönüştürmek ve sonuç dosyasında metin elde etmek için.

**Returns:**
boolean değer

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Madde işareti tanımını etkinleştir.

**Returns:**
boolean değer

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Fontların yeniden kaydedilme prosedürünü alır veya ayarlar. True olarak ayarlanırsa, önceki font özelliklerinin etkisini önlemek için her sayfada fontları yeniden yükler ve yeni oluşturulan fontu baştan yükler. Performansı artırmak istiyorsanız bu seçeneği false olarak ayarlayın. Varsayılan değer true;

**Returns:**
boolean değer

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Paragraf veya satır sonlarını kullan

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Type3 fontları için dönüşümü alır veya ayarlar. Type 3 fontlarda, glifler grafik operatör akışlarıyla tanımlanır. Bu, DOC/DOCX çıktısında metin yerine görüntüler gördüğümüz anlamına gelir. Bu bayrağı true olarak ayarlayın, Type3 fontları TTF'ye dönüştürmek ve sonuç dosyasında metin elde etmek için.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir, örn.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Çıktı formatını ayarla

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Dönüştürülen görüntülerin X çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Dönüştürülen görüntülerin Y çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Bu parametre, metin satırlarını paragraflara gruplamak için kullanılır. İki göreceli metin satırının ne kadar uzakta olabileceğini belirler. Metin satırının yüksekliğinin yüzde yüzler içinde belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Bellek içinde kaydetme modunda dönüştürürken geçici verileri tutacak yolu (dosya adı veya dizin adı) tanımlar.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Tanıma modu.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Madde işareti tanımını etkinleştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

Pdf'de kelimeler, harflerini veya hecelerini bağımsız olarak yazdıran operatörlerle içsel olarak temsil edilebilir. Bu nedenle, kelimeleri tespit etmek için bazen aslında kelime olan bağımsız karakter gruplarını algılamamız gerekir. Bu ayar, kaynak PDF'deki kelimelerin tanınması sırasında kelimeler arasındaki mesafe olarak kabul edilmesi gereken metin öğeleri (harfler, heceler) arasındaki boşluk genişliğini tanımlar. (Harflar arasındaki en az bu genişlikteki boşluk, metin öğelerinin farklı kelimelere ait olduğunu gösterir). Font boyutuna göre normlanmıştır – 1.0, varsayılan kelime font boyutunun %100'ü anlamına gelir. DİKKAT! Bu yalnızca kaynak PDF, optimal değerin fonttan hesaplanamadığı nadir kullanılan belirli fontları içerdiğinde kullanılır. Dolayısıyla, çoğu durumda bu parametre sonuç belgesinde hiçbir değişiklik yapmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Göreceli yakınlık |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Fontların yeniden kaydedilme prosedürünü alır veya ayarlar. True olarak ayarlanırsa, önceki font özelliklerinin etkisini önlemek için her sayfada fontları yeniden yükler ve yeni oluşturulan fontu baştan yükler. Performansı artırmak istiyorsanız bu seçeneği false olarak ayarlayın. Varsayılan değer true;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
