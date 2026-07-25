---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذه الفئة تحتوي على علامات للتحكم في تحويل PDF/A للحالات التي لا يتطابق فيها مستند PDF المصدر مع مواصفات PDF. إذا تم استخدام علامات هذه الفئة فإنها تقلل."
type: docs
weight: 3740
url: /ar/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

هذه الفئة تحتفظ بأعلام للتحكم في تحويل PDF/A للحالات التي لا يتطابق فيها مستند PDF المصدر مع مواصفات PDF. إذا تم استخدام أعلام هذه الفئة فإنها تقلل الأداء ولكنها ضرورية عندما لا يمكن تحويل مستند PDF المصدر إلى صيغة PDF/A بالطريقة المعتادة. بشكل افتراضي يتم تعيين جميع الأعلام إلى false.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | بعض مستندات PDF تحتوي على خطوط لها أسماء مختلفة في البيانات الداخلية. استخدام هذه العلامة يفرض منطق معالجة خاصة للحالات التي تكون فيها حقول BaseFont و FontDescriptor.FontName مختلفة. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | بعض مستندات PDF تحتوي على خطوط لها أسماء مختلفة في البيانات الداخلية. استخدام هذه العلامة يفرض منطق معالجة خاصة للحالات التي تكون فيها حقول BaseFont و FontDescriptor.FontName مختلفة. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

منشئ

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

بعض مستندات PDF تحتوي على خطوط لها أسماء مختلفة في البيانات الداخلية. استخدام هذه العلامة يفرض منطق معالجة خاصة للحالات التي تكون فيها حقول BaseFont و FontDescriptor.FontName مختلفة.

**Returns:**
قيمة منطقية

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

بعض مستندات PDF تحتوي على خطوط لها أسماء مختلفة في البيانات الداخلية. استخدام هذه العلامة يفرض منطق معالجة خاصة للحالات التي تكون فيها حقول BaseFont و FontDescriptor.FontName مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
