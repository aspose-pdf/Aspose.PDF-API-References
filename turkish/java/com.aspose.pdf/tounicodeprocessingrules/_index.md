---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, Adobe Preflight hatası \"Text cannot be mapped to Unicode\" hatasını çözmek için kullanılabilecek kuralları açıklar."
type: docs
weight: 5380
url: /tr/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Bu sınıf, Adobe Preflight hatası "Metin Unicode'a eşlenemiyor" sorununu çözmek için kullanılabilecek kuralları tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Yeni bir {@link ToUnicodeProcessingRules} sınıfı örneği başlatır. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | CMap adlarından boşlukları kaldırmak için belirtilen seçenekle yeni bir {@link ToUnicodeProcessingRules} sınıfı örneği başlatır. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Belirtilen seçeneklerle yeni bir {@link ToUnicodeProcessingRules} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Bazı yazı tipleri bazı metin sembolleri için unicode bilgisi sağlamaz. Bu bilgi eksikliği "Text cannot be mapped to Unicode" hatasını tetikler. Bu bayrağı, bağlantısız sembolleri unicode "space" (kod 32) olarak eşlemek için kullanın. |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Bazı yazı tiplerinin ToUnicode karakter kod haritalarında adlarda boşluklar bulunur. Bu boşluklar unicode metin eşlemesinde hatalara neden olabilir. Bu bayrak, ToUnicode karakter kod haritalarının adlarından boşlukları kaldırmayı sağlar. Varsayılan olarak false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Bazı yazı tipleri bazı metin sembolleri için unicode bilgisi sağlamaz. Bu bilgi eksikliği "Text cannot be mapped to Unicode" hatasını tetikler. Bu bayrağı, bağlantısız sembolleri unicode "space" (kod 32) olarak eşlemek için kullanın. |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Bazı yazı tiplerinin ToUnicode karakter kod haritalarında adlarda boşluklar bulunur. Bu boşluklar unicode metin eşlemesinde hatalara neden olabilir. Bu bayrak, ToUnicode karakter kod haritalarının adlarından boşlukları kaldırmayı sağlar. Varsayılan olarak false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Yeni bir {@link ToUnicodeProcessingRules} sınıfı örneği başlatır.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

CMap adlarından boşlukları kaldırmak için belirtilen seçenekle yeni bir {@link ToUnicodeProcessingRules} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeSpaces |  | CMap adlarından boşlukları kaldırıp kaldırmayacağını belirten bir boolean değer. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Belirtilen seçeneklerle yeni bir {@link ToUnicodeProcessingRules} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeSpaces |  | CMap adlarından boşlukların kaldırılıp kaldırılmayacağını gösterir. |
| mapNonLinkedUnicodesOnSpace |  | Bağlantısız Unicode sembollerinin boşluklara eşlenip eşlenmeyeceğini gösterir. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Bazı yazı tipleri bazı metin sembolleri için unicode bilgisi sağlamaz. Bu bilgi eksikliği "Text cannot be mapped to Unicode" hatasını tetikler. Bu bayrağı, bağlantısız sembolleri unicode "space" (kod 32) olarak eşlemek için kullanın.

**Returns:**
boolean değer

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Bazı yazı tiplerinin ToUnicode karakter kod haritalarında adlarda boşluklar bulunur. Bu boşluklar unicode metin eşlemesinde hatalara neden olabilir. Bu bayrak, ToUnicode karakter kod haritalarının adlarından boşlukları kaldırmayı sağlar. Varsayılan olarak false.

**Returns:**
boolean değer

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Bazı yazı tipleri bazı metin sembolleri için unicode bilgisi sağlamaz. Bu bilgi eksikliği "Text cannot be mapped to Unicode" hatasını tetikler. Bu bayrağı, bağlantısız sembolleri unicode "space" (kod 32) olarak eşlemek için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Bazı yazı tiplerinin ToUnicode karakter kod haritalarında adlarda boşluklar bulunur. Bu boşluklar unicode metin eşlemesinde hatalara neden olabilir. Bu bayrak, ToUnicode karakter kod haritalarının adlarından boşlukları kaldırmayı sağlar. Varsayılan olarak false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
