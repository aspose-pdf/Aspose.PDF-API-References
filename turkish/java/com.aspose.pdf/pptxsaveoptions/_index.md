---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "SVG formatına dışa aktarma için kaydetme seçenekleri."
type: docs
weight: 3950
url: /tr/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

SVG formatına dışa aktarma için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir; örneğin işlenen sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir, konsolda ilerlemeyi gösteren işleyici kod örneği: </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | Görüntü çözünürlüğünü (dpi) alır veya ayarlar. Varsayılan değer 192 dpi'dir. |
| [getSeparateImages](#getSeparateImages--) | Doğru olarak ayarlanırsa, görüntüler diğer tüm grafiklerden ayrılır. |
| [getSlidesAsImages](#getSlidesAsImages--) | Doğru olarak ayarlanırsa, tüm içerik görüntüler olarak tanınır (sayfa başına bir). |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | Metin sütunları tanıma özelliğini değiştirir. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir, örn. |
| [setImageResolution](#setImageResolution-int-) | Görüntü çözünürlüğünü (dpi) alır veya ayarlar. Varsayılan değer 192 dpi'dir. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | Metin sütunları tanıma özelliğini değiştirir. |
| [setSeparateImages](#setSeparateImages-boolean-) | Doğru olarak ayarlanırsa, görüntüler diğer tüm grafiklerden ayrılır. |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | Doğru olarak ayarlanırsa, tüm içerik görüntüler olarak tanınır (sayfa başına bir). |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

Yapıcı

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir; örneğin işlenen sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir, konsolda ilerlemeyi gösteren işleyici kod örneği: </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler örneği

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

Görüntü çözünürlüğünü (dpi) alır veya ayarlar. Varsayılan değer 192 dpi'dir.

**Returns:**
int değer

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

Doğru olarak ayarlanırsa, görüntüler diğer tüm grafiklerden ayrılır.

**Returns:**
boolean değer

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

Doğru olarak ayarlanırsa, tüm içerik görüntüler olarak tanınır (sayfa başına bir).

**Returns:**
boolean değer

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

Metin sütunları tanıma özelliğini değiştirir.

**Returns:**
boolean değer

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Bu işleyici, dönüşüm ilerleme olaylarını ele almak için kullanılabilir, örn.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

Görüntü çözünürlüğünü (dpi) alır veya ayarlar. Varsayılan değer 192 dpi'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

Metin sütunları tanıma özelliğini değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

Doğru olarak ayarlanırsa, görüntüler diğer tüm grafiklerden ayrılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

Doğru olarak ayarlanırsa, tüm içerik görüntüler olarak tanınır (sayfa başına bir).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
