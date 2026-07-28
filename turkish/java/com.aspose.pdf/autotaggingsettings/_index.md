---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgelerinde otomatik etiketleme işlevi için ayarları sağlar. {@link AutoTaggingSettings} sınıfı, PDF içeriğinin otomatik etiketlenmesi için seçenekleri yapılandırmaya izin verir. Bu."
type: docs
weight: 230
url: /tr/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

PDF belgelerinde otomatik etiketleme işlevi için ayarları sağlar. {@link AutoTaggingSettings} sınıfı, PDF içeriğinin otomatik etiketlenmesi için seçeneklerin yapılandırılmasına izin verir. Otomatik etiketlemeyi etkinleştirme veya devre dışı bırakma, başlık tanıma stratejisini belirleme ve yazı tipi boyutlarına göre başlık seviyelerini tanımlama özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefault](#getDefault--) | PDF belgelerinde otomatik etiketleme işlevi için varsayılan ayarları alır. Varsayılan ayarlar otomatik etiketlemeyi etkinleştirir ve başlık tanıma için otomatik stratejiyi kullanır. Bu ayarlar, PDF formatı dönüşümü veya PDF içeriğinin otomatik etiketlenmesini gerektiren diğer işlemler için temel bir yapılandırma olarak kullanılabilir. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Auto-tagging işlevinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Etkinleştirildiğinde, auto-tagging işlevi PDF belgesi için otomatik olarak etiketli içerik oluşturur; bu, erişilebilirliği ve yapıyı iyileştirebilir. |
| [getHeadingLevels](#getHeadingLevels--) | PDF belgesindeki başlıkların yapısını belirlemek için kullanılan başlık seviyelerini alır veya ayarlar. {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) özelliği, yazı tipi boyutlarını başlık seviyelerine eşleştirmeyi yapılandırmaya izin verir. Bu, otomatik etiketleme sürecinde belgedeki metin öğelerinin yazı tipi boyutuna göre uygun başlık seviyelerini tanımlamak ve atamak için kullanılır. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Belge içinde otomatik etiketleme sırasında başlıkları tanımak için kullanılan stratejiyi alır veya ayarlar. {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) özelliği, belge içinde başlıkların nasıl tanımlandığını belirler. Mevcut stratejiler, başlıkları taslaklara, sezgisel analize veya otomatik algılamaya dayalı olarak tanımayı içerir. Bu özelliği {@link HeadingRecognitionStrategy#None} olarak ayarlamak, başlık tanımayı devre dışı bırakır. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Auto-tagging işlevinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Etkinleştirildiğinde, auto-tagging işlevi PDF belgesi için otomatik olarak etiketli içerik oluşturur; bu, erişilebilirliği ve yapıyı iyileştirebilir. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | PDF belgesindeki başlıkların yapısını belirlemek için kullanılan başlık seviyelerini alır veya ayarlar. {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) özelliği, yazı tipi boyutlarını başlık seviyelerine eşleştirmeyi yapılandırmaya izin verir. Bu, otomatik etiketleme sürecinde belgedeki metin öğelerinin yazı tipi boyutuna göre uygun başlık seviyelerini tanımlamak ve atamak için kullanılır. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Belge içinde otomatik etiketleme sırasında başlıkları tanımak için kullanılan stratejiyi alır veya ayarlar. {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) özelliği, belge içinde başlıkların nasıl tanımlandığını belirler. Mevcut stratejiler, başlıkları taslaklara, sezgisel analize veya otomatik algılamaya dayalı olarak tanımayı içerir. Bu özelliği {@link HeadingRecognitionStrategy#None} olarak ayarlamak, başlık tanımayı devre dışı bırakır. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

PDF belgelerinde otomatik etiketleme işlevi için varsayılan ayarları alır. Varsayılan ayarlar otomatik etiketlemeyi etkinleştirir ve başlık tanıma için otomatik stratejiyi kullanır. Bu ayarlar, PDF formatı dönüşümü veya PDF içeriğinin otomatik etiketlenmesini gerektiren diğer işlemler için temel bir yapılandırma olarak kullanılabilir.

**Returns:**
AutoTaggingSettings örneği

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Auto-tagging işlevinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Etkinleştirildiğinde, auto-tagging işlevi PDF belgesi için otomatik olarak etiketli içerik oluşturur; bu, erişilebilirliği ve yapıyı iyileştirebilir.

**Returns:**
boolean değer

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

PDF belgesindeki başlıkların yapısını belirlemek için kullanılan başlık seviyelerini alır veya ayarlar. {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) özelliği, yazı tipi boyutlarını başlık seviyelerine eşleştirmeyi yapılandırmaya izin verir. Bu, otomatik etiketleme sürecinde belgedeki metin öğelerinin yazı tipi boyutuna göre uygun başlık seviyelerini tanımlamak ve atamak için kullanılır.

**Returns:**
HeadingLevels örneği

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Belge içinde otomatik etiketleme sırasında başlıkları tanımak için kullanılan stratejiyi alır veya ayarlar. {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) özelliği, belge içinde başlıkların nasıl tanımlandığını belirler. Mevcut stratejiler, başlıkları taslaklara, sezgisel analize veya otomatik algılamaya dayalı olarak tanımayı içerir. Bu özelliği {@link HeadingRecognitionStrategy#None} olarak ayarlamak, başlık tanımayı devre dışı bırakır.

**Returns:**
HeadingRecognitionStrategy öğesi

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Auto-tagging işlevinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Etkinleştirildiğinde, auto-tagging işlevi PDF belgesi için otomatik olarak etiketli içerik oluşturur; bu, erişilebilirliği ve yapıyı iyileştirebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
PDF belgesindeki başlıkların yapısını belirlemek için kullanılan başlık seviyelerini alır veya ayarlar. {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) özelliği, yazı tipi boyutlarını başlık seviyelerine eşleştirmeyi yapılandırmaya izin verir. Bu, otomatik etiketleme sürecinde belgedeki metin öğelerinin yazı tipi boyutuna göre uygun başlık seviyelerini tanımlamak ve atamak için kullanılır.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Belge içinde otomatik etiketleme sırasında başlıkları tanımak için kullanılan stratejiyi alır veya ayarlar. {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) özelliği, belge içinde başlıkların nasıl tanımlandığını belirler. Mevcut stratejiler, başlıkları taslaklara, sezgisel analize veya otomatik algılamaya dayalı olarak tanımayı içerir. Bu özelliği {@link HeadingRecognitionStrategy#None} olarak ayarlamak, başlık tanımayı devre dışı bırakır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | HeadingRecognitionStrategy öğesi |
