---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "إذا كان خاصية SplitToPages في HtmlSaveOptions مفعلة، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء تحويل PDF إلى HTML. تمثل هذه الفئة مجموعة من."
type: docs
weight: 2100
url: /ar/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

إذا كان خاصية SplitToPages في HtmlSaveOptions مفعلة، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة محوّلة) أثناء تحويل PDF إلى HTML. هذه الفئة تمثل مجموعة من البيانات المتعلقة بالحفظ المخصص لعلامات صفحة HTML واحدة أثناء تحويل PDF إلى HTML.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getContentStream](#getContentStream--) | يتم تعيينه بواسطة المحول. يمثل HTML المحفوظ كتيار. |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تحتوي هذه الخاصية على ترتيب ملف صفحة HTML المحفوظة. يمكن استخدام الخاصية في منطق الكود المخصص لتحديد كيفية معالجة صفحة HTML أو أين يتم حفظها، وإذا تم إيقاف تقسيم الصفحات فإن هذه القيمة دائمًا تكون '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة كبيرة للمستند الأصلي بالكامل. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تخبر هذه الخاصية الكود المخصص من أي صفحة في PDF الأصلي تم إنشاء علامة HTML المحفوظة. إذا كان رقم الصفحة الأصلي غير معروف لسبب ما أو SplitToPages=false، فإن هذه الخاصية دائمًا تحتوي على '0' مما يشير إلى أن المحول لا يمكنه توفير رقم الصفحة الأصلي الدقيق لملف علامة HTML المقدم. |
| [getSupposedFileName](#getSupposedFileName--) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية معالجة المحتوى أو أين يتم حفظه. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | يجب تعيينه في الكود المخصص عند الحاجة. يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا كان لسبب ما يجب معالجة علامة HTML المقدمة ليس عبر الكود المخصص بل عبر كود المحول نفسه بالطريقة القياسية للمحول. وبالتالي، ضبط هذه العلامة في الكود المخصص يعني أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه. |
| [setContentStream](#setContentStream-java.io.InputStream-) | يتم تعيينه بواسطة المحول. يمثل HTML المحفوظ كتيار. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | يجب تعيينه في الكود المخصص عند الحاجة. يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا كان لسبب ما يجب معالجة علامة HTML المقدمة ليس عبر الكود المخصص بل عبر كود المحول نفسه بالطريقة القياسية للمحول. وبالتالي، ضبط هذه العلامة في الكود المخصص يعني أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تحتوي هذه الخاصية على ترتيب ملف صفحة HTML المحفوظة. يمكن استخدام الخاصية في منطق الكود المخصص لتحديد كيفية معالجة صفحة HTML أو أين يتم حفظها، وإذا تم إيقاف تقسيم الصفحات فإن هذه القيمة دائمًا تكون '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة كبيرة للمستند الأصلي بالكامل. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تخبر هذه الخاصية الكود المخصص من أي صفحة في PDF الأصلي تم إنشاء علامة HTML المحفوظة. إذا كان رقم الصفحة الأصلي غير معروف لسبب ما أو SplitToPages=false، فإن هذه الخاصية دائمًا تحتوي على '0' مما يشير إلى أن المحول لا يمكنه توفير رقم الصفحة الأصلي الدقيق لملف علامة HTML المقدم. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية معالجة المحتوى أو أين يتم حفظه. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

يتم تعيينه بواسطة المحول. يمثل HTML المحفوظ كتيار.

**Returns:**
مثيل InputStream

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تحتوي هذه الخاصية على ترتيب ملف صفحة HTML المحفوظة. يمكن استخدام الخاصية في منطق الكود المخصص لتحديد كيفية معالجة صفحة HTML أو أين يتم حفظها، وإذا تم إيقاف تقسيم الصفحات فإن هذه القيمة دائمًا تكون '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة كبيرة للمستند الأصلي بالكامل.

**Returns:**
قيمة int

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تخبر هذه الخاصية الكود المخصص من أي صفحة في PDF الأصلي تم إنشاء علامة HTML المحفوظة. إذا كان رقم الصفحة الأصلي غير معروف لسبب ما أو SplitToPages=false، فإن هذه الخاصية دائمًا تحتوي على '0' مما يشير إلى أن المحول لا يمكنه توفير رقم الصفحة الأصلي الدقيق لملف علامة HTML المقدم.

**Returns:**
قيمة int

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية معالجة المحتوى أو أين يتم حفظه.

**Returns:**
قيمة سلسلة

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

يجب تعيينه في الكود المخصص عند الحاجة. يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا كان لسبب ما يجب معالجة علامة HTML المقدمة ليس عبر الكود المخصص بل عبر كود المحول نفسه بالطريقة القياسية للمحول. وبالتالي، ضبط هذه العلامة في الكود المخصص يعني أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه.

**Returns:**
قيمة منطقية

### setContentStream {#setContentStream-java.io.InputStream-}
يتم تعيينه بواسطة المحول. يمثل HTML المحفوظ كتيار.

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

يجب تعيينه في الكود المخصص عند الحاجة. يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا كان لسبب ما يجب معالجة علامة HTML المقدمة ليس عبر الكود المخصص بل عبر كود المحول نفسه بالطريقة القياسية للمحول. وبالتالي، ضبط هذه العلامة في الكود المخصص يعني أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| customProcessingCancelled |  | قيمة منطقية |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تحتوي هذه الخاصية على ترتيب ملف صفحة HTML المحفوظة. يمكن استخدام الخاصية في منطق الكود المخصص لتحديد كيفية معالجة صفحة HTML أو أين يتم حفظها، وإذا تم إيقاف تقسيم الصفحات فإن هذه القيمة دائمًا تكون '1' لأنه في هذه الحالة يتم إنشاء صفحة HTML واحدة كبيرة للمستند الأصلي بالكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlHostPageNumber |  | قيمة int |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

يتم تعيينه بواسطة المحول. إذا تم تفعيل خاصية SplitToPages، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة تم تحويلها) أثناء عملية التحويل. تخبر هذه الخاصية الكود المخصص من أي صفحة في PDF الأصلي تم إنشاء علامة HTML المحفوظة. إذا كان رقم الصفحة الأصلي غير معروف لسبب ما أو SplitToPages=false، فإن هذه الخاصية دائمًا تحتوي على '0' مما يشير إلى أن المحول لا يمكنه توفير رقم الصفحة الأصلي الدقيق لملف علامة HTML المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfHostPageNumber |  | قيمة int |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
يتم تعيينه بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة. يمكن استخدامه في الكود المخصص لتحديد كيفية معالجة المحتوى أو أين يتم حفظه.
