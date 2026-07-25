---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة أساسية مجردة لقطع الترقيم في مستند."
type: docs
weight: 3460
url: /ar/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

يمثل فئة أساسية مجردة لقطع الترقيم في مستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEndPage](#getEndPage--) | يحصل أو يضبط رقم الصفحة النهائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 0. إذا تم تعيين قيمة أقل من 0، سيتم تعديلها إلى 0. القيمة الافتراضية 0 تعني عدم وجود حدود للصفحة النهائية. |
| [getStartPage](#getStartPage--) | يحصل أو يضبط رقم الصفحة الابتدائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، سيتم تعديلها إلى 1. |
| [getSubset](#getSubset--) | يحصل أو يضبط مجموعة الصفحات التي ينطبق عليها العنصر (مثال: جميع الصفحات، الصفحات الزوجية، الصفحات الفردية). |
| [setEndPage](#setEndPage-int-) | يحصل أو يضبط رقم الصفحة النهائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 0. إذا تم تعيين قيمة أقل من 0، سيتم تعديلها إلى 0. القيمة الافتراضية 0 تعني عدم وجود حدود للصفحة النهائية. |
| [setStartPage](#setStartPage-int-) | يحصل أو يضبط رقم الصفحة الابتدائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، سيتم تعديلها إلى 1. |
| [setSubset](#setSubset-int-) | يحصل أو يضبط مجموعة الصفحات التي ينطبق عليها العنصر (مثال: جميع الصفحات، الصفحات الزوجية، الصفحات الفردية). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

يحصل أو يضبط رقم الصفحة النهائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 0. إذا تم تعيين قيمة أقل من 0، سيتم تعديلها إلى 0. القيمة الافتراضية 0 تعني عدم وجود حدود للصفحة النهائية.

**Returns:**
قيمة int

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

يحصل أو يضبط رقم الصفحة الابتدائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، سيتم تعديلها إلى 1.

**Returns:**
قيمة int

### getSubset {#getSubset--}
```
public final int getSubset()
```

يحصل أو يضبط مجموعة الصفحات التي ينطبق عليها العنصر (مثال: جميع الصفحات، الصفحات الزوجية، الصفحات الفردية).

**Returns:**
قيمة int

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

يحصل أو يضبط رقم الصفحة النهائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 0. إذا تم تعيين قيمة أقل من 0، سيتم تعديلها إلى 0. القيمة الافتراضية 0 تعني عدم وجود حدود للصفحة النهائية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

يحصل أو يضبط رقم الصفحة الابتدائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، سيتم تعديلها إلى 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

يحصل أو يضبط مجموعة الصفحات التي ينطبق عليها العنصر (مثال: جميع الصفحات، الصفحات الزوجية، الصفحات الفردية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
