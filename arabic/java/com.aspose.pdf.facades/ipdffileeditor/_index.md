---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تنفّذ عمليات على ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيّب، إلخ."
type: docs
weight: 290
url: /ar/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

تنفّذ عمليات على ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيّب، إلخ.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | يضيف الصفحات التي تم اختيارها من مصفوفة المستندات في portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | يضيف الصفحات التي تم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | يضيف الصفحات التي تم اختيارها من مستندات portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | يضيف الصفحات التي تم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | يجمع المستندات. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | يجمع الملفات |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | يجمع ملفين. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | يجمع الملفات في ملف واحد. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | يجمع ملفين. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف Pdf جديد. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف PDF جديد. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | هو السماح باستثناءات الجمع |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية. |
| [getContentDisposition](#getContentDisposition--) | يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | يحصل على سجل عملية التحويل. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج. |
| [getLastException](#getLastException--) | يحصل على آخر استثناء حدث. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | إذا كانت true، يتم دمج المخططات المتكررة. |
| [getOwnerPassword](#getOwnerPassword--) | يحصل على كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا. |
| [getPreserveUserRights](#getPreserveUserRights--) | إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج. |
| [getRemoveSignatures](#getRemoveSignatures--) | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة. |
| [getSaveOptions](#getSaveOptions--) | يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | احصل على تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عندما يتم دمج النماذج. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | يدرج صفحات من ملف آخر في ملف Pdf الإدخال. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | يدرج صفحات من ملف آخر في ملف Pdf الإدخال. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | يدرج صفحات من ملف آخر في ملف Pdf الإدخال. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | يدرج صفحات من ملف آخر في ملف Pdf في موقع معين. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | ينشئ كتيبًا من InputStream إلى outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | ينشئ كتيبًا من firstInputStream إلى outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | ينشئ كتيبًا من inputFile إلى outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | ينشئ مستند N-Up من تدفقَي PDF إلى outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | ينشئ مستند N-Up من firstInputFile إلى outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | ينشئ مستند N-Up من ملف الإدخال إلى outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مستند N-Up من ملفي PDF إلى outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | إذا تم تعيينه إلى true، تُرمى الاستثناءات إذا حدث خطأ. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يحدد كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | إذا كانت true، يتم دمج المخططات المتكررة. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | يحدد كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يحدد خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | حدد تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream ملف جديد. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |
| [splitToPages](#splitToPages-java.io.InputStream-) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد. |
| [splitToPages](#splitToPages-java.lang.String-) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
يضيف الصفحات التي تم اختيارها من مصفوفة المستندات في portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
يضيف الصفحات التي تم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
يضيف الصفحات التي تم اختيارها من مستندات portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
يضيف الصفحات التي تم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
يجمع المستندات.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
يجمع الملفات

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
يجمع ملفين.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
يجمع الملفات في ملف واحد.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
يجمع ملفين.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف Pdf جديد.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف PDF جديد.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

هو السماح باستثناءات الجمع

**Returns:**
قيمة منطقية

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق.

**Returns:**
قيمة السلسلة

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية.

**Returns:**
قيمة منطقية

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse.

**Returns:**
عنصر ContentDisposition

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

يحصل على سجل عملية التحويل.

**Returns:**
قيمة السلسلة

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا.

**Returns:**
عنصر ConcatenateCorruptedFileAction

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج.

**Returns:**
قيمة منطقية

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج.

**Returns:**
قيمة منطقية

### getLastException {#getLastException--}
```
Exception getLastException()
```

يحصل على آخر استثناء حدث.

**Returns:**
كائن java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true.

**Returns:**
قيمة منطقية

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

إذا كانت true، يتم دمج المخططات المتكررة.

**Returns:**
قيمة منطقية

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

يحصل على كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا.

**Returns:**
قيمة السلسلة

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج.

**Returns:**
قيمة منطقية

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة.

**Returns:**
قيمة منطقية

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse.

**Returns:**
كائن SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

احصل على تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عندما يتم دمج النماذج.

**Returns:**
قيمة السلسلة

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
يدرج صفحات من ملف آخر في ملف Pdf الإدخال.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
يدرج صفحات من ملف آخر في ملف Pdf الإدخال.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
يدرج صفحات من ملف آخر في ملف Pdf الإدخال.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
يدرج صفحات من ملف آخر في ملف Pdf في موقع معين.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
ينشئ كتيبًا من InputStream إلى outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
ينشئ كتيبًا من firstInputStream إلى outputStream.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
ينشئ كتيبًا من inputFile إلى outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
ينشئ مستند N-Up من تدفقَي PDF إلى outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
ينشئ مستند N-Up من firstInputFile إلى outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
ينشئ مستند N-Up من ملف الإدخال إلى outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
ينشئ مستند N-Up من ملفي PDF إلى outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

إذا تم تعيينه إلى true، تُرمى الاستثناءات إذا حدث خطأ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يحدد كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ConcatenateCorruptedFileAction |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

إذا كانت true، يتم دمج المخططات المتكررة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
يحدد كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يحدد خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
حدد تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream ملف جديد.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد.

### splitToPages {#splitToPages-java.io.InputStream-}
يقسم ملف PDF إلى مستندات صفحة واحدة.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد.

### splitToPages {#splitToPages-java.lang.String-}
يقسم ملف PDF إلى مستندات صفحة واحدة.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد.
