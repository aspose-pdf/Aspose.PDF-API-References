---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة للتحقق من تعرض توقيعات المستند الرقمية للانتهاك."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

يمثل فئة للتحقق من تعرض توقيعات المستند الرقمية للانتهاك.

## الحقول

| حقل | الوصف |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | يحصل على مجموعة من التوقيعات الرقمية التي تم تحديدها على أنها مخترقة. تحتوي هذه الخاصية على قائمة بجميع التوقيعات المخترقة التي تم اكتشافها في المستند. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | يحصل على حالة تغطية التوقيعات الرقمية في المستند. إذا كانت مساوية لـ {@code SignaturesCoverage#Undefined}، فإن أحد التوقيعات يكون مخترقًا. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | يشير إلى ما إذا كان هناك أي توقيعات رقمية مخترقة في المستند. يرجع true إذا كان هناك توقيع واحد على الأقل مخترق؛ وإلا false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

يحصل على مجموعة من التوقيعات الرقمية التي تم تحديدها على أنها مخترقة. تحتوي هذه الخاصية على قائمة بجميع التوقيعات المخترقة التي تم اكتشافها في المستند.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

يحصل على حالة تغطية التوقيعات الرقمية في المستند. إذا كانت مساوية لـ {@code SignaturesCoverage#Undefined}، فإن أحد التوقيعات يكون مخترقًا.

**Returns:**
عنصر SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

يشير إلى ما إذا كان هناك أي توقيعات رقمية مخترقة في المستند. يرجع true إذا كان هناك توقيع واحد على الأقل مخترق؛ وإلا false.

**Returns:**
قيمة منطقية
