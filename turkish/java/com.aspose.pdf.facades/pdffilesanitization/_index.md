---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Aspose.PDF for Java API Referansı"
description: "Temizleme ve kurtarma API'sini temsil eder. Belgeleri başka bir şekilde oluşturamıyorsanız/aydınlayamıyorsanız kullanın."
type: docs
weight: 510
url: /tr/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Temizleme ve kurtarma API'sini temsil eder. Belgeleri başka bir şekilde oluşturamıyorsanız/aydınlayamıyorsanız kullanın.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Yeni bir örnek başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Sanitizasyon için bir Pdf akışı bağlar. |
| [bindPdf](#bindPdf-java.lang.String-) | Sanitizasyon için bir Pdf dosyasını bağlar. |
| [close](#close--) | Facade'i kapatır. |
| [getLog](#getLog--) | Dosya kaydedildikten sonra dosyayla ne yapıldığını kontrol edebilirsiniz. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Belge için yeni xref ve trailer oluşturulmasına izin verir. |
| [getUseTrimBottom](#getUseTrimBottom--) | Pdf verisinin sonrasındaki verilerin kaldırılmasına izin verir. |
| [getUseTrimTop](#getUseTrimTop--) | Pdf verisinin öncesindeki verilerin kaldırılmasına izin verir. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Eski xref ve trailer'ı kaldırır ve yeni bir xref ve trailer oluşturur. |
| [recover](#recover--) | Belgeyi kurtarır. Özelleştirmek için özellikleri kullanın. |
| [save](#save-java.io.OutputStream-) | Sonuç PDF'yi akışa kaydeder. |
| [save](#save-java.lang.String-) | Sonuç PDF'yi dosyaya kaydeder. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Belge için yeni xref ve trailer oluşturulmasına izin verir. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Pdf verisinin sonrasındaki verilerin kaldırılmasına izin verir. |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Pdf verisinin öncesindeki verilerin kaldırılmasına izin verir. |
| [trimBottom](#trimBottom--) | Son %%EOF'den sonraki verileri kaldırır. |
| [trimTop](#trimTop--) | %PDF'den önceki verileri kaldırır. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Yeni bir örnek başlatır.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.io.InputStream-}
Sanitizasyon için bir Pdf akışı bağlar.

### bindPdf {#bindPdf-java.lang.String-}
Sanitizasyon için bir Pdf dosyasını bağlar.

### close {#close--}
```
public void close()
```

Facade'i kapatır.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Dosya kaydedildikten sonra dosyayla ne yapıldığını kontrol edebilirsiniz.

**Returns:**
String öğelerinin listesi

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Belge için yeni xref ve trailer oluşturulmasına izin verir.

**Returns:**
boolean değer

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Pdf verisinin sonrasındaki verilerin kaldırılmasına izin verir.

**Returns:**
boolean değer

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Pdf verisinin öncesindeki verilerin kaldırılmasına izin verir.

**Returns:**
boolean değer

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Eski xref ve trailer'ı kaldırır ve yeni bir xref ve trailer oluşturur.

### recover {#recover--}
```
public final void recover()
```

Belgeyi kurtarır. Özelleştirmek için özellikleri kullanın.

### save {#save-java.io.OutputStream-}
Sonuç PDF'yi akışa kaydeder.

### save {#save-java.lang.String-}
Sonuç PDF'yi dosyaya kaydeder.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Belge için yeni xref ve trailer oluşturulmasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Pdf verisinin sonrasındaki verilerin kaldırılmasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Pdf verisinin öncesindeki verilerin kaldırılmasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Son %%EOF'den sonraki verileri kaldırır.

### trimTop {#trimTop--}
```
public final void trimTop()
```

%PDF'den önceki verileri kaldırır.
