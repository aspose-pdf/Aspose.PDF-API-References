---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kaynağın özel yüklenmesinin sonucu"
type: docs
weight: 2820
url: /tr/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Kaynağın özel yüklenmesinin sonucu

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Yükleme sonucunun bir örneğini oluşturur |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getData](#getData--) | Özel yükleyiciyle yüklenen ikili veri - yüklemeden sonra ayarlanmalıdır |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Bazen kaynağın kodlaması yüklemeden sonra veya yükleme sırasında bilinir. Böyle bir durumda özel kod, bu parametre aracılığıyla dönüştürücüye bu bilgiyi sağlayabilir. Kodlama bilinmiyorsa veya önemsizse bu parametrede null bırakabilirsiniz. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Bazen bir sebeple istenen kaynağın yüklenmesi mümkün olmayabilir. Kaynağın bulunamaması genellikle dönüşümlerin çökmesine neden olmaz ve sonuç belge yine de oluşturulabilir (ancak belki biraz daha düşük kaliteyle, görüntüler olmadan vb.). Yükleme sırasında bir istisna oluşursa, sadece yakalayın ve bu parametreye koyun – bazen bu bilgi, dönüştürücünün sonucu render etmesi için faydalı olur. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Bazen yüklenen kaynağın MIME türü hakkındaki bilgi, dönüştürücü için faydalıdır. Bu parametrede MIME türünü (yüklemeden sonra biliniyorsa) sağlayabilirsiniz. MIME türü bilinmiyorsa veya sağlanması gerekli değilse lütfen parametreyi null bırakın. |
| [isLoadingCancelled](#isLoadingCancelled--) | Bazen bazı sebeplerle yükleme, özel kod tarafından gerçekleşmemelidir. Böyle bir durumda lütfen bu bayrağı True olarak ayarlayın. Bu durumda dönüştürücü, (özel strateji sağlanmadığında olduğu gibi) sonucu elde etmek için dahili varsayılan kaynak yükleyiciyi kullanmaya çalışacaktır. |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Bazen kaynağın kodlaması yüklemeden sonra veya yükleme sırasında bilinir. Böyle bir durumda özel kod, bu parametre aracılığıyla dönüştürücüye bu bilgiyi sağlayabilir. Kodlama bilinmiyorsa veya önemsizse bu parametrede null bırakabilirsiniz. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Bazen bir sebeple istenen kaynağın yüklenmesi mümkün olmayabilir. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Bazen bazı sebeplerle yükleme, özel kod tarafından gerçekleşmemelidir. Böyle bir durumda lütfen bu bayrağı True olarak ayarlayın. Bu durumda dönüştürücü, (özel strateji sağlanmadığında olduğu gibi) sonucu elde etmek için dahili varsayılan kaynak yükleyiciyi kullanmaya çalışacaktır. |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Bazen yüklenen kaynağın MIME türü hakkındaki bilgi, dönüştürücü için faydalıdır. Bu parametrede MIME türünü (yüklemeden sonra biliniyorsa) sağlayabilirsiniz. MIME türü bilinmiyorsa veya sağlanması gerekli değilse lütfen parametreyi null bırakın. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Yükleme sonucunun bir örneğini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri |  | özel yüklemenin sonucu her zaman sağlanmalıdır, eğer herhangi bir sonuç elde etmek mümkün değilse sıfır uzunlukta bir dizi olabilir |

### getData {#getData--}
```
public byte[] getData()
```

Özel yükleyiciyle yüklenen ikili veri - yüklemeden sonra ayarlanmalıdır

**Returns:**
bayt değerleri dizisi

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Bazen kaynağın kodlaması yüklemeden sonra veya yükleme sırasında bilinir. Böyle bir durumda özel kod, bu parametre aracılığıyla dönüştürücüye bu bilgiyi sağlayabilir. Kodlama bilinmiyorsa veya önemsizse bu parametrede null bırakabilirsiniz.

**Returns:**
Charset örneği

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Bazen bir sebeple istenen kaynağın yüklenmesi mümkün olmayabilir. Kaynağın bulunamaması genellikle dönüşümlerin çökmesine neden olmaz ve sonuç belge yine de oluşturulabilir (ancak belki biraz daha düşük kaliteyle, görüntüler olmadan vb.). Yükleme sırasında bir istisna oluşursa, sadece yakalayın ve bu parametreye koyun – bazen bu bilgi, dönüştürücünün sonucu render etmesi için faydalı olur.

**Returns:**
İstisna

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Bazen yüklenen kaynağın MIME türü hakkındaki bilgi, dönüştürücü için faydalıdır. Bu parametrede MIME türünü (yüklemeden sonra biliniyorsa) sağlayabilirsiniz. MIME türü bilinmiyorsa veya sağlanması gerekli değilse lütfen parametreyi null bırakın.

**Returns:**
String değeri

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Bazen bazı sebeplerle yükleme, özel kod tarafından gerçekleşmemelidir. Böyle bir durumda lütfen bu bayrağı True olarak ayarlayın. Bu durumda dönüştürücü, (özel strateji sağlanmadığında olduğu gibi) sonucu elde etmek için dahili varsayılan kaynak yükleyiciyi kullanmaya çalışacaktır.

**Returns:**
boolean değer

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Bazen kaynağın kodlaması yüklemeden sonra veya yükleme sırasında bilinir. Böyle bir durumda özel kod, bu parametre aracılığıyla dönüştürücüye bu bilgiyi sağlayabilir. Kodlama bilinmiyorsa veya önemsizse bu parametrede null bırakabilirsiniz.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Bazen bir sebeple istenen kaynağın yüklenmesi mümkün olmayabilir.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Bazen bazı sebeplerle yükleme, özel kod tarafından gerçekleşmemelidir. Böyle bir durumda lütfen bu bayrağı True olarak ayarlayın. Bu durumda dönüştürücü, (özel strateji sağlanmadığında olduğu gibi) sonucu elde etmek için dahili varsayılan kaynak yükleyiciyi kullanmaya çalışacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loadingCancelled |  | boolean değer |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Bazen yüklenen kaynağın MIME türü hakkındaki bilgi, dönüştürücü için faydalıdır. Bu parametrede MIME türünü (yüklemeden sonra biliniyorsa) sağlayabilirsiniz. MIME türü bilinmiyorsa veya sağlanması gerekli değilse lütfen parametreyi null bırakın.
