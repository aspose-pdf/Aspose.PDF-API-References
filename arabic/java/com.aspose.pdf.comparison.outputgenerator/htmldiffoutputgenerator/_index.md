---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لتوليد تمثيل HTML لفروقات النصوص. يتم الإشارة إلى فواصل الأسطر المحذوفة بعلامة الفقرة -."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

يمثل فئة لتوليد تمثيل HTML لفروقات النصوص. يتم الإشارة إلى فواصل الأسطر المحذوفة بعلامة الفقرة -.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | ينشئ مثيلاً من الفئة {@link HtmlDiffOutputGenerator}. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | ينشئ مثيلاً من الفئة {@link HtmlDiffOutputGenerator}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [generateOutput1](#generateOutput1-java.util.List-) | يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | طريقة داخلية |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | يحصل أو يعيّن سلسلة نمط CSS لعملية الحذف. مثال: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | يحصل أو يعيّن سلسلة نمط CSS لعملية المساواة. مثال: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | يحصل أو يعيّن سلسلة نمط CSS لعملية الإدراج. مثال: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | احصل أو عيّن نمط text-decoration: line-through لعملية الحذف. القيمة الافتراضية هي {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | يحصل أو يعيّن سلسلة نمط CSS لعملية الحذف. مثال: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | يحصل أو يعيّن سلسلة نمط CSS لعملية المساواة. مثال: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | يحصل أو يعيّن سلسلة نمط CSS لعملية الإدراج. مثال: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | احصل أو عيّن نمط text-decoration: line-through لعملية الحذف. القيمة الافتراضية هي {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

ينشئ مثيلاً من الفئة {@link HtmlDiffOutputGenerator}.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
ينشئ مثيلاً من الفئة {@link HtmlDiffOutputGenerator}.

### generateOutput {#generateOutput-java.util.List-}
يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف.

### generateOutput1 {#generateOutput1-java.util.List-}
يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
يُولّد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
طريقة داخلية

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

يحصل أو يعيّن سلسلة نمط CSS لعملية الحذف. مثال: color: #003300; background-color: #ccff66;

**Returns:**
قيمة سلسلة

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

يحصل أو يعيّن سلسلة نمط CSS لعملية المساواة. مثال: color: #003300; background-color: #ccff66;

**Returns:**
قيمة سلسلة

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

يحصل أو يعيّن سلسلة نمط CSS لعملية الإدراج. مثال: color: #003300; background-color: #ccff66;

**Returns:**
قيمة سلسلة

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

احصل أو عيّن نمط text-decoration: line-through لعملية الحذف. القيمة الافتراضية هي {@code False}.

**Returns:**
قيمة منطقية

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
يحصل أو يعيّن سلسلة نمط CSS لعملية الحذف. مثال: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
يحصل أو يعيّن سلسلة نمط CSS لعملية المساواة. مثال: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
يحصل أو يعيّن سلسلة نمط CSS لعملية الإدراج. مثال: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

احصل أو عيّن نمط text-decoration: line-through لعملية الحذف. القيمة الافتراضية هي {@code False}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
