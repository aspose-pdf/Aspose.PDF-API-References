---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تصف قطعة Bates Numbering."
type: docs
weight: 290
url: /ar/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

الفئة تصف قطعة Bates Numbering.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | يُنشئ مثلاً جديداً من الفئة {@link BatesNArtifact}. هذا المُنشئ داخلي ويُنشئ مثلاً لعنصر رأس مع القيم الافتراضية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | يحصل أو يضبط عدد الأرقام لترقيم Bates. يجب أن تكون القيمة بين 3 و 15 شاملًا. إذا تم ضبط قيمة أقل من 3، سيتم تعديلها إلى 3. إذا تم ضبط قيمة أكبر من 15، سيتم تعديلها إلى 15. القيمة الافتراضية هي 6. |
| [getPrefix](#getPrefix--) | يحصل أو يضبط البادئة التي ستُضاف إلى رقم Bates. |
| [getStartNumber](#getStartNumber--) | يحصل أو يضبط الرقم الابتدائي لترقيم Bates. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم ضبط قيمة أقل من 1، سيتم تعديلها إلى 1. |
| [getSuffix](#getSuffix--) | يحصل أو يضبط اللاحقة التي ستُضاف إلى رقم Bates. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | يحصل أو يضبط عدد الأرقام لترقيم Bates. يجب أن تكون القيمة بين 3 و 15 شاملًا. إذا تم ضبط قيمة أقل من 3، سيتم تعديلها إلى 3. إذا تم ضبط قيمة أكبر من 15، سيتم تعديلها إلى 15. القيمة الافتراضية هي 6. |
| [setPrefix](#setPrefix-java.lang.String-) | يحصل أو يضبط البادئة التي ستُضاف إلى رقم Bates. |
| [setStartNumber](#setStartNumber-int-) | يحصل أو يضبط الرقم الابتدائي لترقيم Bates. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم ضبط قيمة أقل من 1، سيتم تعديلها إلى 1. |
| [setSuffix](#setSuffix-java.lang.String-) | يحصل أو يضبط اللاحقة التي ستُضاف إلى رقم Bates. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

يُنشئ مثلاً جديداً من الفئة {@link BatesNArtifact}. هذا المُنشئ داخلي ويُنشئ مثلاً لعنصر رأس مع القيم الافتراضية.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

يحصل أو يضبط عدد الأرقام لترقيم Bates. يجب أن تكون القيمة بين 3 و 15 شاملًا. إذا تم ضبط قيمة أقل من 3، سيتم تعديلها إلى 3. إذا تم ضبط قيمة أكبر من 15، سيتم تعديلها إلى 15. القيمة الافتراضية هي 6.

**Returns:**
قيمة int

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

يحصل أو يضبط البادئة التي ستُضاف إلى رقم Bates.

**Returns:**
قيمة سلسلة

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

يحصل أو يضبط الرقم الابتدائي لترقيم Bates. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم ضبط قيمة أقل من 1، سيتم تعديلها إلى 1.

**Returns:**
قيمة int

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

يحصل أو يضبط اللاحقة التي ستُضاف إلى رقم Bates.

**Returns:**
قيمة سلسلة

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

يحصل أو يضبط عدد الأرقام لترقيم Bates. يجب أن تكون القيمة بين 3 و 15 شاملًا. إذا تم ضبط قيمة أقل من 3، سيتم تعديلها إلى 3. إذا تم ضبط قيمة أكبر من 15، سيتم تعديلها إلى 15. القيمة الافتراضية هي 6.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPrefix {#setPrefix-java.lang.String-}
يحصل أو يضبط البادئة التي ستُضاف إلى رقم Bates.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

يحصل أو يضبط الرقم الابتدائي لترقيم Bates. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم ضبط قيمة أقل من 1، سيتم تعديلها إلى 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setSuffix {#setSuffix-java.lang.String-}
يحصل أو يضبط اللاحقة التي ستُضاف إلى رقم Bates.
