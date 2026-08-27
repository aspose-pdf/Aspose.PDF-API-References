---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لاسم التوقيع. يمثل اسم توقيع أكثر دقة. يستخدم بدلاً من أسماء السلاسل. يسمح لك بعرض التوقيعات بنفس أسماء السلاسل."
type: docs
weight: 690
url: /ar/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

يمثل فئة لاسم التوقيع. يمثل اسم توقيع أكثر دقة. يستخدم بدلاً من أسماء السلاسل. يسمح لك بعرض التوقيعات بنفس أسماء السلاسل.

## الحقول

| حقل | الوصف |
| --- | --- |
| [FullName](#FullName) | يحصل على الاسم الكامل للتوقيع، موفرًا معرفًا فريدًا ودقيقًا لحقل التوقيع. |
| [Name](#Name) | يحصل على اسم التوقيع. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة والكائن المحدد متساويين. |
| [getSignatureDictionary](#getSignatureDictionary--) | يحصل على قاموس الت.signature. |
| [hashCode](#hashCode--) | يرجع رمز تجزئة لهذه الحالة بناءً على خاصية FullName. |
| [hasSignature](#hasSignature--) | يشير إلى ما إذا كان التوقيع موجودًا أم لا. |
| [toString](#toString--) | يرجع تمثيلًا نصيًا لعنصر {@link SignatureName}، معتمدًا أساسًا على اسمه. |

### FullName {#FullName}
```
public final String FullName
```

يحصل على الاسم الكامل للتوقيع، موفرًا معرفًا فريدًا ودقيقًا لحقل التوقيع.

### Name {#Name}
```
public final String Name
```

يحصل على اسم التوقيع.

### equals {#equals-java.lang.Object-}
يحدد ما إذا كانت هذه الحالة والكائن المحدد متساويين.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

يحصل على قاموس الت.signature.

**Returns:**
قاموس التوقيع أو null إذا لم يتم العثور عليه.

### hashCode {#hashCode--}
```
public int hashCode()
```

يرجع رمز تجزئة لهذه الحالة بناءً على خاصية FullName.

**Returns:**
عدد صحيح يمثل رمز التجزئة لخاصية FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

يشير إلى ما إذا كان التوقيع موجودًا أم لا.

**Returns:**
قيمة منطقية

### toString {#toString--}
```
public String toString()
```

يرجع تمثيلًا نصيًا لعنصر {@link SignatureName}، معتمدًا أساسًا على اسمه.

**Returns:**
سلسلة تمثل اسم التوقيع.
