---
title: "Kaynaklar"
linktitle: "Kaynaklar"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfa kaynaklarını temsil eden sınıf."
type: docs
weight: 4220
url: /tr/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Sayfa kaynaklarını temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Önbellekteki verileri temizler, belleği serbest bırakır vb. |
| [getExtGStates](#getExtGStates--) | Kaynaklardan tüm ExGStates öğelerini alır. |
| [getFonts](#getFonts--) |  {@code Fonts} kaynak koleksiyonunu alır |
| [getFonts](#getFonts-boolean-) | Font koleksiyonunu döndürür. Kaynaklar font girdisi içermiyorsa, CreateIfAbsent bayrağına bağlı olarak oluşturulur. |
| [getForms](#getForms--) |  {@code Forms} form koleksiyonunu alır |
| [getImages](#getImages--) |  {@code Images} görüntü koleksiyonunu alır |
| [getResourceDictionary](#getResourceDictionary--) | Dahili alan |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Kaynakları alır |
| [isCommonResource](#isCommonResource--) | Bu kaynaklar ortak ise, yani birkaç sayfa arasında paylaşılıyorsa (sayfalar sözlüğünde veya her sayfada nesne referansı olarak yer alıyorsa) doğru olur. Ortak kaynaklarla yapılan işlemler çok dikkatli bir şekilde yürütülmelidir; örneğin bir sayfadaki ortak kaynaklardan bir nesnenin silinmesi, silinen nesne diğer sayfalarda kullanılmışsa diğer sayfalarda hatalara neden olabilir. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Yalnızca dahili kullanım için! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Önbellekteki verileri temizler, belleği serbest bırakır vb.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Kaynaklardan tüm ExGStates öğelerini alır.

**Returns:**
ExGStates ad anahtarlarıyla sözlüğü döndürür.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

 {@code Fonts} kaynak koleksiyonunu alır

**Returns:**
FontCollection nesnesi

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Font koleksiyonunu döndürür. Kaynaklar font girdisi içermiyorsa, CreateIfAbsent bayrağına bağlı olarak oluşturulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createIfAbsent |  | Bu bayrak doğru ise, bu giriş yoksa yazı tipleri oluşturulacaktır. |

**Returns:**
Yazı tipleri koleksiyonu.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

 {@code Forms} form koleksiyonunu alır

**Returns:**
XFormCollection nesnesi

### getImages {#getImages--}
```
public XImageCollection getImages()
```

 {@code Images} görüntü koleksiyonunu alır

**Returns:**
XImageCollection nesnesi

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Dahili alan

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Kaynakları alır

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Bu kaynaklar ortak ise, yani birkaç sayfa arasında paylaşılıyorsa (sayfalar sözlüğünde veya her sayfada nesne referansı olarak yer alıyorsa) doğru olur. Ortak kaynaklarla yapılan işlemler çok dikkatli bir şekilde yürütülmelidir; örneğin bir sayfadaki ortak kaynaklardan bir nesnenin silinmesi, silinen nesne diğer sayfalarda kullanılmışsa diğer sayfalarda hatalara neden olabilir.

**Returns:**
boolean değer

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
Yalnızca dahili kullanım için!
