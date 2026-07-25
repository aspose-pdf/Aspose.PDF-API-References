---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملف صورة المورد الخارجي أثناء تحويل PDF إلى HTML."
type: docs
weight: 2070
url: /ar/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملف صورة المورد الخارجي أثناء تحويل PDF إلى HTML.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | ينشئ نسخة جديدة من HtmlImageSavingInfo |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | يخبر الشيفرة المخصصة بالصفحة التي ينتمي إليها الصورة المحفوظة ضمن مجموعة ملفات HTML المولدة. إذا تم إيقاف تقسيم الصفحات، فإن هذه القيمة دائماً تحتوي على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة فقط. |
| [getImageType](#getImageType--) | يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الشيفرة المخصصة لتحديد ما يجب القيام به. |
| [getParentType](#getParentType--) | يمكن أن تكون الصورة المحفوظة جزءاً من HTML نفسه أو يمكن استخراجها من SVG المدمج في HTML. يمكن لهذه الخاصية إبلاغ الشيفرة المخصصة بنوع العنصر الأب للصورة المعالجة. يتم تعيينها بواسطة المحول ويمكن استخدامها في الشيفرة المخصصة لتحديد ما يجب القيام به مع تلك الصورة (مثلاً يمكن للشيفرة المخصصة تحديد مكان حفظ الصورة أو كيفية الإشارة إليها في محتوى العنصر الأب). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | يخبر الشيفرة المخصصة بالصفحة التي تنتمي إليها الصورة المحفوظة في مستند PDF الأصلي. بما أنه قد لا يتم حفظ جميع صفحات المستند الأصلي، فإن هذه القيمة تشير إلى رقم الصفحة المستضيفة في PDF الأصلي. إذا كان رقم الصفحة الأصلي غير معروف لأي سبب، فإنها دائماً تُرجع '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | يخبر الشيفرة المخصصة بالصفحة التي ينتمي إليها الصورة المحفوظة ضمن مجموعة ملفات HTML المولدة. إذا تم إيقاف تقسيم الصفحات، فإن هذه القيمة دائماً تحتوي على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة فقط. |
| [setImageType](#setImageType-int-) | يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الشيفرة المخصصة لتحديد ما يجب القيام به. |
| [setParentType](#setParentType-int-) | يمكن أن تكون الصورة المحفوظة جزءاً من HTML نفسه أو يمكن استخراجها من SVG المدمج في HTML. يمكن لهذه الخاصية إبلاغ الشيفرة المخصصة بنوع العنصر الأب للصورة المعالجة. يتم تعيينها بواسطة المحول ويمكن استخدامها في الشيفرة المخصصة لتحديد ما يجب القيام به مع تلك الصورة (مثلاً يمكن للشيفرة المخصصة تحديد مكان حفظ الصورة أو كيفية الإشارة إليها في محتوى العنصر الأب). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | يخبر الشيفرة المخصصة بالصفحة التي تنتمي إليها الصورة المحفوظة في مستند PDF الأصلي. بما أنه قد لا يتم حفظ جميع صفحات المستند الأصلي، فإن هذه القيمة تشير إلى رقم الصفحة المستضيفة في PDF الأصلي. إذا كان رقم الصفحة الأصلي غير معروف لأي سبب، فإنها دائماً تُرجع '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

ينشئ نسخة جديدة من HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

يخبر الشيفرة المخصصة بالصفحة التي ينتمي إليها الصورة المحفوظة ضمن مجموعة ملفات HTML المولدة. إذا تم إيقاف تقسيم الصفحات، فإن هذه القيمة دائماً تحتوي على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة فقط.

**Returns:**
قيمة int

### getImageType {#getImageType--}
```
public int getImageType()
```

يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الشيفرة المخصصة لتحديد ما يجب القيام به.

**Returns:**
عنصر HtmlImageType @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

يمكن أن تكون الصورة المحفوظة جزءاً من HTML نفسه أو يمكن استخراجها من SVG المدمج في HTML. يمكن لهذه الخاصية إبلاغ الشيفرة المخصصة بنوع العنصر الأب للصورة المعالجة. يتم تعيينها بواسطة المحول ويمكن استخدامها في الشيفرة المخصصة لتحديد ما يجب القيام به مع تلك الصورة (مثلاً يمكن للشيفرة المخصصة تحديد مكان حفظ الصورة أو كيفية الإشارة إليها في محتوى العنصر الأب).

**Returns:**
عنصر ImageParentTypes @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

يخبر الشيفرة المخصصة بالصفحة التي تنتمي إليها الصورة المحفوظة في مستند PDF الأصلي. بما أنه قد لا يتم حفظ جميع صفحات المستند الأصلي، فإن هذه القيمة تشير إلى رقم الصفحة المستضيفة في PDF الأصلي. إذا كان رقم الصفحة الأصلي غير معروف لأي سبب، فإنها دائماً تُرجع '1'.

**Returns:**
قيمة int

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

يخبر الشيفرة المخصصة بالصفحة التي ينتمي إليها الصورة المحفوظة ضمن مجموعة ملفات HTML المولدة. إذا تم إيقاف تقسيم الصفحات، فإن هذه القيمة دائماً تحتوي على '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlHostPageNumber |  | قيمة int |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

يمثل نوع الصورة المحفوظة المشار إليها في HTML. يتم تعيينه بواسطة المحول ويمكن استخدامه في الشيفرة المخصصة لتحديد ما يجب القيام به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageType |  | عنصر HtmlImageType @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

يمكن أن تكون الصورة المحفوظة جزءاً من HTML نفسه أو يمكن استخراجها من SVG المدمج في HTML. يمكن لهذه الخاصية إبلاغ الشيفرة المخصصة بنوع العنصر الأب للصورة المعالجة. يتم تعيينها بواسطة المحول ويمكن استخدامها في الشيفرة المخصصة لتحديد ما يجب القيام به مع تلك الصورة (مثلاً يمكن للشيفرة المخصصة تحديد مكان حفظ الصورة أو كيفية الإشارة إليها في محتوى العنصر الأب).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parentType |  | عنصر ImageParentTypes @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

يخبر الشيفرة المخصصة بالصفحة التي تنتمي إليها الصورة المحفوظة في مستند PDF الأصلي. بما أنه قد لا يتم حفظ جميع صفحات المستند الأصلي، فإن هذه القيمة تشير إلى رقم الصفحة المستضيفة في PDF الأصلي. إذا كان رقم الصفحة الأصلي غير معروف لأي سبب، فإنها دائماً تُرجع '1'.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfHostPageNumber |  | قيمة int |
