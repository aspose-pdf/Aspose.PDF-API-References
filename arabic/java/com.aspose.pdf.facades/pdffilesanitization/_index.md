---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل واجهة برمجة تطبيقات التطهير والاستعادة. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى."
type: docs
weight: 510
url: /ar/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

يمثل واجهة برمجة تطبيقات التطهير والاستعادة. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | يُهيئ نسخة جديدة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.io.InputStream-) | يربط تدفق Pdf للتنظيف. |
| [bindPdf](#bindPdf-java.lang.String-) | يربط ملف Pdf للتنقية. |
| [close](#close--) | يغلق الواجهة. |
| [getLog](#getLog--) | بعد حفظ الملف يمكنك التحقق مما تم عمله على الملف. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | يسمح بإنشاء xref و trailer جديدين للمستند. |
| [getUseTrimBottom](#getUseTrimBottom--) | يسمح بإزالة البيانات بعد بيانات pdf. |
| [getUseTrimTop](#getUseTrimTop--) | يسمح بإزالة البيانات قبل بيانات pdf. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | يزيل xref القديم مع trailer وينشئ xref جديد مع trailer. |
| [recover](#recover--) | يستعيد المستند. استخدم الخصائص للتخصيص. |
| [save](#save-java.io.OutputStream-) | يحفظ PDF الناتج إلى التدفق. |
| [save](#save-java.lang.String-) | يحفظ PDF الناتج إلى ملف. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | يسمح بإنشاء xref و trailer جديدين للمستند. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | يسمح بإزالة البيانات بعد بيانات pdf. |
| [setUseTrimTop](#setUseTrimTop-boolean-) | يسمح بإزالة البيانات قبل بيانات pdf. |
| [trimBottom](#trimBottom--) | يزيل البيانات بعد آخر %%EOF. |
| [trimTop](#trimTop--) | يزيل البيانات قبل %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

يُهيئ نسخة جديدة.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.io.InputStream-}
يربط تدفق Pdf للتنظيف.

### bindPdf {#bindPdf-java.lang.String-}
يربط ملف Pdf للتنقية.

### close {#close--}
```
public void close()
```

يغلق الواجهة.

### getLog {#getLog--}
```
public final List < String > getLog()
```

بعد حفظ الملف يمكنك التحقق مما تم عمله على الملف.

**Returns:**
قائمة من عناصر String

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

يسمح بإنشاء xref و trailer جديدين للمستند.

**Returns:**
قيمة منطقية

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

يسمح بإزالة البيانات بعد بيانات pdf.

**Returns:**
قيمة منطقية

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

يسمح بإزالة البيانات قبل بيانات pdf.

**Returns:**
قيمة منطقية

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

يزيل xref القديم مع trailer وينشئ xref جديد مع trailer.

### recover {#recover--}
```
public final void recover()
```

يستعيد المستند. استخدم الخصائص للتخصيص.

### save {#save-java.io.OutputStream-}
يحفظ PDF الناتج إلى التدفق.

### save {#save-java.lang.String-}
يحفظ PDF الناتج إلى ملف.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

يسمح بإنشاء xref و trailer جديدين للمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

يسمح بإزالة البيانات بعد بيانات pdf.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

يسمح بإزالة البيانات قبل بيانات pdf.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

يزيل البيانات بعد آخر %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

يزيل البيانات قبل %PDF.
