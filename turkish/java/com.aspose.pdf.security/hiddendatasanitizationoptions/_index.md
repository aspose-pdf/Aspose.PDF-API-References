---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir belge içindeki gizli verileri temizlemek için yapılandırma seçeneklerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Bir belge içindeki gizli verileri temizlemek için yapılandırma seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [all](#all--) | Tüm seçenekleri sanitasyon için ayarlanmış {@link HiddenDataSanitizationOptions} sınıfının yeni bir örneğini oluşturur. Bu, ek açıklamaların, JavaScript'in, meta verilerin, eklerin, arama dizininin, özel bilgilerin kaldırılmasını etkinleştirmeyi, formların ve katmanların düzleştirilmesini içerir ve sayfaları görüntülere dönüştürme seçeneğini devre dışı bırakır. Örneği elde ettikten sonra {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) veya {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) gibi isteğe bağlı yapılandırmalar manuel olarak değiştirilebilir, çünkü varsayılan olarak etkin değildirler. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Sayfaları görüntülere dönüştürme seçeneğini alır. Bu seçenek etkinleştirilirse, ImageCompressionOptions seçeneği yok sayılacaktır. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir. Sayfaların görüntülere dönüştürülmesi, diğer seçenekler tarafından kontrol edilen ana gizli veriler temizlendikten sonra gerçekleşecektir. |
| [getFlattenForms](#getFlattenForms--) | Belgenin içindeki formların sanitasyon sürecinde düzleştirilip düzleştirilmeyeceğini gösteren bir değer alır. Formları düzleştirmek, etkileşimli form alanlarını statik içeriğe dönüştürür ve bunları düzenlenemez veya doldurulamaz hâle getirir. |
| [getFlattenLayers](#getFlattenLayers--) | PDF belgesindeki katmanları düzleştirme seçeneğini alır. Etkinleştirildiğinde, belgedeki tüm katmanlar tek bir katmanda birleştirilir ve ayrı yapıları kaldırılır. Bu seçenek, içeriği basitleştirerek ve katmanlarda gizli veri bulunmadığından emin olarak belgeleri sanitasyon için kullanışlıdır. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Belge görüntüsü dönüştürme seçeneğini alır. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir. |
| [getImageDpi](#getImageDpi--) | Dönüştürme sırasında sayfa görüntülerini çözümleme seçeneğini alır. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Belgeden ek açıklamaları kaldırıp kaldırmayacağını gösteren bir değer alır. Etkinleştirildiğinde, belgede bulunan tüm ek açıklamalar sanitasyon sürecinde kaldırılır. Kırpma ek açıklamaları uygulanacaktır. |
| [getRemoveAttachments](#getRemoveAttachments--) | Belgeden tüm ekli dosyaları kaldırma seçeneğini alır. Etkinleştirildiğinde, PDF içindeki tüm eklerin sanitasyon sürecinde ortadan kaldırılmasını sağlar. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Belgeden JavaScript ve ilişkili eylemlerin kaldırılıp kaldırılmayacağını gösteren bir değer alır. Bu seçenek, gömülü betiklerin oluşturabileceği potansiyel güvenlik açıklarını ortadan kaldırmak için faydalıdır. |
| [getRemoveMetadata](#getRemoveMetadata--) | Belgeden meta verileri kaldırma seçeneğini alır. true olarak ayarlanırsa, belge özellikleri ve ek gömülü meta veri bilgileri gibi meta veriler sanitasyon sırasında kaldırılacaktır. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Belgeden arama dizini ve özel bilgilerin kaldırılıp kaldırılmayacağını gösteren bir değer alır. Gömülü arama dizinlerinin ve özel verilerin kaldırılmasını etkinleştirerek belge güvenliğini ve gizliliğini artırır. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Sayfaları görüntülere dönüştürme seçeneğini ayarlar. Bu seçenek etkinleştirilirse, ImageCompressionOptions seçeneği yok sayılacaktır. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir. Sayfaların görüntülere dönüştürülmesi, diğer seçenekler tarafından kontrol edilen ana gizli veriler temizlendikten sonra gerçekleşecektir. |
| [setFlattenForms](#setFlattenForms-boolean-) | Belgedeki formların sanitasyon sürecinde düzleştirilip düzleştirilmeyeceğini gösteren bir değeri ayarlar. Formları düzleştirmek, etkileşimli form alanlarını statik içeriğe dönüştürür ve bunları düzenlenemez veya doldurulamaz hâle getirir. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | PDF belgesindeki katmanları düzleştirme seçeneğini ayarlar. Etkinleştirildiğinde, belgedeki tüm katmanlar tek bir katmanda birleştirilir ve ayrı yapıları kaldırılır. Bu seçenek, içeriği basitleştirerek ve katmanlarda gizli veri bulunmadığından emin olarak belgeleri sanitasyon için kullanışlıdır. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Belge görüntüsü dönüştürme seçeneğini ayarlar. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir. |
| [setImageDpi](#setImageDpi-int-) | Dönüştürme sırasında sayfa görüntülerini çözümleme seçeneğini ayarlar. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Belgeden ek açıklamaları kaldırıp kaldırmayacağını gösteren bir değeri ayarlar. Etkinleştirildiğinde, belgede bulunan tüm ek açıklamalar sanitasyon sürecinde kaldırılır. Kırpma ek açıklamaları uygulanacaktır. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Belgeden tüm ekli dosyaları kaldırma seçeneğini ayarlar. Etkinleştirildiğinde, PDF içindeki tüm eklerin temizlik işlemi sırasında ortadan kaldırılmasını sağlar. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Belgeden JavaScript ve ilişkili eylemlerin kaldırılıp kaldırılmayacağını gösteren bir değer ayarlar. Bu seçenek, gömülü betiklerin oluşturabileceği potansiyel güvenlik açıklarını ortadan kaldırmak için faydalıdır. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Belgeden meta verileri kaldırma seçeneğini ayarlar. True olarak ayarlanırsa, belge özellikleri ve ek gömülü meta veri bilgileri gibi meta veriler temizlik sırasında kaldırılacaktır. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Belgeden arama dizini ve özel bilgilerin kaldırılıp kaldırılmayacağını gösteren bir değer ayarlar. Gömülü arama dizinlerinin ve özel verilerin kaldırılmasını sağlayarak belge güvenliğini ve gizliliğini artırır. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Tüm seçenekleri sanitasyon için ayarlanmış {@link HiddenDataSanitizationOptions} sınıfının yeni bir örneğini oluşturur. Bu, ek açıklamaların, JavaScript'in, meta verilerin, eklerin, arama dizininin, özel bilgilerin kaldırılmasını etkinleştirmeyi, formların ve katmanların düzleştirilmesini içerir ve sayfaları görüntülere dönüştürme seçeneğini devre dışı bırakır. Örneği elde ettikten sonra {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) veya {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) gibi isteğe bağlı yapılandırmalar manuel olarak değiştirilebilir, çünkü varsayılan olarak etkin değildirler.

**Returns:**
Tüm temizlik seçenekleri önceden yapılandırılmış bir {@link HiddenDataSanitizationOptions} örneği.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Sayfaları görüntülere dönüştürme seçeneğini alır. Bu seçenek etkinleştirilirse, ImageCompressionOptions seçeneği yok sayılacaktır. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir. Sayfaların görüntülere dönüştürülmesi, diğer seçenekler tarafından kontrol edilen ana gizli veriler temizlendikten sonra gerçekleşecektir.

**Returns:**
sayfaları görüntülere dönüştürme seçeneği.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Belgenin içindeki formların sanitasyon sürecinde düzleştirilip düzleştirilmeyeceğini gösteren bir değer alır. Formları düzleştirmek, etkileşimli form alanlarını statik içeriğe dönüştürür ve bunları düzenlenemez veya doldurulamaz hâle getirir.

**Returns:**
Belgedeki formların temizlik işlemi sırasında düzleştirilip düzleştirilmeyeceğini gösteren bir değer.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

PDF belgesindeki katmanları düzleştirme seçeneğini alır. Etkinleştirildiğinde, belgedeki tüm katmanlar tek bir katmanda birleştirilir ve ayrı yapıları kaldırılır. Bu seçenek, içeriği basitleştirerek ve katmanlarda gizli veri bulunmadığından emin olarak belgeleri sanitasyon için kullanışlıdır.

**Returns:**
PDF belgesindeki katmanları düzleştirme seçeneği.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Belge görüntüsü dönüştürme seçeneğini alır. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir.

**Returns:**
belge görüntü dönüşüm seçeneği.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Dönüştürme sırasında sayfa görüntülerini çözümleme seçeneğini alır.

**Returns:**
dönüştürme sırasında sayfa görüntülerini çözümleme seçeneği.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Belgeden ek açıklamaları kaldırıp kaldırmayacağını gösteren bir değer alır. Etkinleştirildiğinde, belgede bulunan tüm ek açıklamalar sanitasyon sürecinde kaldırılır. Kırpma ek açıklamaları uygulanacaktır.

**Returns:**
Belgeden ek açıklamaların kaldırılıp kaldırılmayacağını gösteren bir değer.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Belgeden tüm ekli dosyaları kaldırma seçeneğini alır. Etkinleştirildiğinde, PDF içindeki tüm eklerin sanitasyon sürecinde ortadan kaldırılmasını sağlar.

**Returns:**
belgeden tüm ekli dosyaları kaldırma seçeneği.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Belgeden JavaScript ve ilişkili eylemlerin kaldırılıp kaldırılmayacağını gösteren bir değer alır. Bu seçenek, gömülü betiklerin oluşturabileceği potansiyel güvenlik açıklarını ortadan kaldırmak için faydalıdır.

**Returns:**
Belgeden JavaScript ve ilişkili eylemlerin kaldırılıp kaldırılmayacağını gösteren bir değer.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Belgeden meta verileri kaldırma seçeneğini alır. true olarak ayarlanırsa, belge özellikleri ve ek gömülü meta veri bilgileri gibi meta veriler sanitasyon sırasında kaldırılacaktır.

**Returns:**
belgeden meta verileri kaldırma seçeneği.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Belgeden arama dizini ve özel bilgilerin kaldırılıp kaldırılmayacağını gösteren bir değer alır. Gömülü arama dizinlerinin ve özel verilerin kaldırılmasını etkinleştirerek belge güvenliğini ve gizliliğini artırır.

**Returns:**
Belgeden arama dizini ve özel bilgilerin kaldırılıp kaldırılmayacağını gösteren bir değer.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Sayfaları görüntülere dönüştürme seçeneğini ayarlar. Bu seçenek etkinleştirilirse, ImageCompressionOptions seçeneği yok sayılacaktır. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir. Sayfaların görüntülere dönüştürülmesi, diğer seçenekler tarafından kontrol edilen ana gizli veriler temizlendikten sonra gerçekleşecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | sayfaları görüntülere dönüştürme seçeneği. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Belgedeki formların sanitasyon sürecinde düzleştirilip düzleştirilmeyeceğini gösteren bir değeri ayarlar. Formları düzleştirmek, etkileşimli form alanlarını statik içeriğe dönüştürür ve bunları düzenlenemez veya doldurulamaz hâle getirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Belgedeki formların temizlik işlemi sırasında düzleştirilip düzleştirilmeyeceğini gösteren bir değer. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

PDF belgesindeki katmanları düzleştirme seçeneğini ayarlar. Etkinleştirildiğinde, belgedeki tüm katmanlar tek bir katmanda birleştirilir ve ayrı yapıları kaldırılır. Bu seçenek, içeriği basitleştirerek ve katmanlarda gizli veri bulunmadığından emin olarak belgeleri sanitasyon için kullanışlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PDF belgesindeki katmanları düzleştirme seçeneği. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Belge görüntüsü dönüştürme seçeneğini ayarlar. Gerekli ise {@code #All()} yöntemi kullanılırken seçenek manuel olarak etkinleştirilmelidir.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Dönüştürme sırasında sayfa görüntülerini çözümleme seçeneğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dönüştürme sırasında sayfa görüntülerini çözümleme seçeneği. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Belgeden ek açıklamaları kaldırıp kaldırmayacağını gösteren bir değeri ayarlar. Etkinleştirildiğinde, belgede bulunan tüm ek açıklamalar sanitasyon sürecinde kaldırılır. Kırpma ek açıklamaları uygulanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Belgeden ek açıklamaların kaldırılıp kaldırılmayacağını gösteren bir değer. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Belgeden tüm ekli dosyaları kaldırma seçeneğini ayarlar. Etkinleştirildiğinde, PDF içindeki tüm eklerin temizlik işlemi sırasında ortadan kaldırılmasını sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | belgeden tüm ekli dosyaları kaldırma seçeneği. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Belgeden JavaScript ve ilişkili eylemlerin kaldırılıp kaldırılmayacağını gösteren bir değer ayarlar. Bu seçenek, gömülü betiklerin oluşturabileceği potansiyel güvenlik açıklarını ortadan kaldırmak için faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Belgeden JavaScript ve ilişkili eylemlerin kaldırılıp kaldırılmayacağını gösteren bir değer. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Belgeden meta verileri kaldırma seçeneğini ayarlar. True olarak ayarlanırsa, belge özellikleri ve ek gömülü meta veri bilgileri gibi meta veriler temizlik sırasında kaldırılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | belgeden meta verileri kaldırma seçeneği. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Belgeden arama dizini ve özel bilgilerin kaldırılıp kaldırılmayacağını gösteren bir değer ayarlar. Gömülü arama dizinlerinin ve özel verilerin kaldırılmasını sağlayarak belge güvenliğini ve gizliliğini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Belgeden arama dizini ve özel bilgilerin kaldırılıp kaldırılmayacağını gösteren bir değer. |
