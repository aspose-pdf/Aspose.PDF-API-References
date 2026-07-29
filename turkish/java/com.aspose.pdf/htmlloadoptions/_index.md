---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "HTML dosyasının PDF belgesine yüklenmesi/ithal edilmesi için seçenekleri temsil eder."
type: docs
weight: 1960
url: /tr/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

HTML dosyasının PDF belgesine yüklenmesi/ithal edilmesi için seçenekleri temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Boş temel yol ile html'i pdf belgesine dönüştürmek için yükleme seçenekleri oluşturur. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Boş temel yol ile html'i pdf belgesine dönüştürmek için yükleme seçenekleri oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBasePath](#getBasePath--) | HTML dosyası için temel yol/URL. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Bazen dış kaynakların (görüntüler veya CSS'ler gibi) dahili yükleyicisinin kullanılmasını önlemek ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir. Örneğin, bulutta Aspose.PDF kullanılırken başvurulan dosyalara doğrudan erişim mümkün değildir: bu durumda bazı müşteri kodunun özel bir yönteme yerleştirilmesi gerekir ve bu yönteme referans veren temsilci bu özelliğe atanmalıdır. |
| [getHtmlMediaType](#getHtmlMediaType--) | Renderleme sırasında kullanılan olası medya türlerini alır veya ayarlar. |
| [getInputEncoding](#getInputEncoding--) | Bu belgeyi ayrıştırma sırasında kullanılan kodlamayı belirten özelliği alır. Bu özellik null ise kodlama, belge karakter seti özelliğinden belirlenecektir. |
| [getPageInfo](#getPageInfo--) | Belge sayfa bilgilerini alır |
| [getPageLayoutOption](#getPageLayoutOption--) | Düzen seçeneğini alır veya ayarlar. |
| [isEmbedFonts](#isEmbedFonts--) | Sonuç belgesine gömülen yazı tiplerini alır veya ayarlar. |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | @page kurallarının css içinde tanımlanmasının PageInfo içinde tanımlanan değerleri geçersiz kılacağını belirten bayrağı alır veya ayarlar. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Tüm belgeyi tek sayfaya renderlemeyi alır veya ayarlar. |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Bazen dış kaynakların (görüntüler veya CSS'ler gibi) dahili yükleyicisinin kullanılmasını önlemek ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Sonuç belgesine gömülen yazı tiplerini alır veya ayarlar. |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Renderleme sırasında kullanılan olası medya türlerini alır veya ayarlar. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Bu belgeyi ayrıştırma sırasında kullanılan kodlamayı belirten özelliği ayarlar. Bu özellik null ise kodlama, belge karakter seti özelliğinden belirlenecektir. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Belge sayfa bilgilerini ayarlar |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Düzen seçeneğini alır veya ayarlar. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | @page kurallarının css içinde tanımlanmasının PageInfo içinde tanımlanan değerleri geçersiz kılacağını belirten bayrağı alır veya ayarlar. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Tüm belgeyi tek sayfaya renderlemeyi alır veya ayarlar. |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Boş temel yol ile html'i pdf belgesine dönüştürmek için yükleme seçenekleri oluşturur.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Boş temel yol ile html'i pdf belgesine dönüştürmek için yükleme seçenekleri oluşturur.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

HTML dosyası için temel yol/URL.

**Returns:**
String değeri

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Bazen dış kaynakların (görüntüler veya CSS'ler gibi) dahili yükleyicisinin kullanılmasını önlemek ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir. Örneğin, bulutta Aspose.PDF kullanılırken başvurulan dosyalara doğrudan erişim mümkün değildir: bu durumda bazı müşteri kodunun özel bir yönteme yerleştirilmesi gerekir ve bu yönteme referans veren temsilci bu özelliğe atanmalıdır.

**Returns:**
ResourceLoadingStrategy örneği

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Renderleme sırasında kullanılan olası medya türlerini alır veya ayarlar.

**Returns:**
HtmlMediaType öğesi

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Bu belgeyi ayrıştırma sırasında kullanılan kodlamayı belirten özelliği alır. Bu özellik null ise kodlama, belge karakter seti özelliğinden belirlenecektir.

**Returns:**
String değeri

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Belge sayfa bilgilerini alır

**Returns:**
sayfa bilgisi

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Düzen seçeneğini alır veya ayarlar.

**Returns:**
HtmlPageLayoutOption öğesi @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Sonuç belgesine gömülen yazı tiplerini alır veya ayarlar.

**Returns:**
boolean değer

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

@page kurallarının css içinde tanımlanmasının PageInfo içinde tanımlanan değerleri geçersiz kılacağını belirten bayrağı alır veya ayarlar.

**Returns:**
boolean değer

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Tüm belgeyi tek sayfaya renderlemeyi alır veya ayarlar.

**Returns:**
boolean değer

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Bazen dış kaynakların (görüntüler veya CSS'ler gibi) dahili yükleyicisinin kullanılmasını önlemek ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Sonuç belgesine gömülen yazı tiplerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Renderleme sırasında kullanılan olası medya türlerini alır veya ayarlar.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Bu belgeyi ayrıştırma sırasında kullanılan kodlamayı belirten özelliği ayarlar. Bu özellik null ise kodlama, belge karakter seti özelliğinden belirlenecektir.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Belge sayfa bilgilerini ayarlar

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Düzen seçeneğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | HtmlPageLayoutOption öğesi @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

@page kurallarının css içinde tanımlanmasının PageInfo içinde tanımlanan değerleri geçersiz kılacağını belirten bayrağı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Tüm belgeyi tek sayfaya renderlemeyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
