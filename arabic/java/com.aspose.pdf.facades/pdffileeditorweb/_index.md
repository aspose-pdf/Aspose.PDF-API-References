---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة PdfFileEditorWeb التي تنفذ عمليات مع ملف PDF: الدمج، التقسيم، استخراج الصفحات، إنشاء كتيب، إلخ."
type: docs
weight: 480
url: /ar/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

يمثل فئة PdfFileEditorWeb التي تنفذ عمليات مع ملف PDF: الدمج، التقسيم، استخراج الصفحات، إنشاء كتيب، إلخ.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | منشئ PdfFileEditorWeb. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن الاستجابة. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | يضيف الصفحات التي تم اختيارها من مصفوفة المستندات في portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | يضيف الصفحات التي تم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن HttpServletResponse. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | يضيف الصفحات التي تم اختيارها من مستندات portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | يضيف الصفحات التي تم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | يجمع المستندات. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | يقوم بدمج الملفات ويخزن النتيجة في كائن HttpServletResponse. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | يجمع الملفات |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | يجمع ملفين. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | يقوم بدمج الملفات ويحفظ النتيجة في كائن HttpResposnse. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | يجمع الملفات في ملف واحد. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | يجمع ملفين. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | يحذف الصفحات المحددة من المستند ويحفظ النتيجة في كائن HttpServletResponse. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | يحذف الصفحات المحددة من المستند ويخزن النتيجة في كائن HttpServletResponse. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpServletResponse. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف Pdf جديد. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpServletResponse. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف PDF جديد. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | مهمل. هذه الخاصية مهملة ولا يمكن استخدامها للسماح برمي الاستثناءات. |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | عدد المستندات المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true. |
| [getContentDisposition](#getContentDisposition--) | يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | يحصل على سجل عملية التحويل. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | إذا كانت true، يتم نسخ البنية المنطقية للملف عند تنفيذ الدمج. |
| [getCopyOutlines](#getCopyOutlines--) | إذا كانت true، سيتم نسخ المخططات. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا. |
| [getCorruptedItems](#getCorruptedItems--) | مصفوفة من المشكلات التي تم مواجهتها عند تنفيذ الدمج. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | تمثيل لمعالج أحداث التقدم الداخلي الذي يعمل أثناء الدمج ويترجم أحداث الدمج لمراحل الدمج الداخلية إلى كود العميل الخارجي. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج. |
| [getKeepActions](#getKeepActions--) | إذا كانت true، سيتم نسخ الإجراءات من المستندات المصدر. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج. |
| [getLastException](#getLastException--) | يحصل على آخر استثناء حدث. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | إذا كانت true، يتم دمج المخططات المتكررة. |
| [getOptimizeSize](#getOptimizeSize--) | يحصل أو يضبط علم التحسين. |
| [getOwnerPassword](#getOwnerPassword--) | يحصل على كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا. |
| [getPreserveUserRights](#getPreserveUserRights--) | إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج. |
| [getRemoveSignatures](#getRemoveSignatures--) | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة. |
| [getSaveOptions](#getSaveOptions--) | يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | احصل على تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عندما يتم دمج النماذج. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | يُدرج المستند في مستند آخر ويخزن النتيجة في كائن الاستجابة. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | يدرج صفحات من ملف آخر في ملف Pdf الإدخال. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | يدرج صفحات من ملف آخر في ملف Pdf الإدخال. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | يُدرج محتويات الملف في الملف المصدر ويخزن النتيجة في كائن HttpServletResponse. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | يدرج صفحات من ملف آخر في ملف Pdf الإدخال. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | يدرج صفحات من ملف آخر في ملف Pdf في موقع معين. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | في بعض الأحيان تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجانب بعضها. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | ينشئ كتيبًا من InputStream إلى outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | ينشئ كتيبًا من firstInputStream إلى outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | إنشاء كتيب من ملف PDF وتخزينه في HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | ينشئ كتيبًا من inputFile إلى outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | ينشئ مستند N-Up من تدفقَي PDF إلى outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | ينشئ مستندًا N-up ويخزن النتيجة في HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | ينشئ مستندًا N-up ويخزن النتيجة في كائن HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | ينشئ مستندًا N-up ويخزن النتيجة في HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | ينشئ مستندًا N-up ويخزن النتيجة في كائن HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | ينشئ مستند N-Up من firstInputFile إلى outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | ينشئ مستند N-Up من ملف الإدخال إلى outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مستند N-Up من ملفي PDF إلى outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | يغيّر حجم محتويات الصفحات في المستند. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | يغيّر حجم محتويات الصفحات في المستند. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يغيّر حجم محتويات الصفحات في المستند. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | مهمل. هذه الخاصية مهملة ولا يمكن استخدامها للسماح برمي الاستثناءات. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | عدد المستندات المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يحدد كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | إذا كانت true، يتم نسخ البنية المنطقية للملف عند تنفيذ الدمج. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | إذا كانت true، سيتم نسخ المخططات. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | تمثيل لمعالج أحداث التقدم الداخلي الذي يعمل أثناء الدمج ويترجم أحداث الدمج لمراحل الدمج الداخلية إلى كود العميل الخارجي. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج. |
| [setKeepActions](#setKeepActions-boolean-) | إذا كانت true، سيتم نسخ الإجراءات من المستندات المصدر. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | إذا كانت true، يتم دمج المخططات المتكررة. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | يحصل أو يضبط علم التحسين. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | يحدد كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يحدد خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | في بعض الأحيان تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجانب بعضها. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | حدد تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | يقسم المستند من البداية إلى الموقع المحدد ويخزن النتيجة في كائن HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | يقسم المستند من الصفحة الأولى إلى الموقع ويحفظ النتيجة في كائنات HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي في كائن HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream ملف جديد. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي في كائن HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |
| [splitToPages](#splitToPages-java.io.InputStream-) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد. |
| [splitToPages](#splitToPages-java.lang.String-) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

منشئ PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن الاستجابة.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
يضيف الصفحات التي تم اختيارها من مصفوفة المستندات في portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
يضيف الصفحات التي تم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن HttpServletResponse.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
يضيف الصفحات التي تم اختيارها من مستندات portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
يضيف الصفحات التي تم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
يجمع المستندات.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
يقوم بدمج الملفات ويخزن النتيجة في كائن HttpServletResponse.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
يجمع الملفات

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
يجمع ملفين.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
يقوم بدمج الملفات ويحفظ النتيجة في كائن HttpResposnse.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
يجمع الملفات في ملف واحد.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
يجمع ملفين.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
يدمج مستندين Pdf في مستند Pdf جديد مع صفحات بترتيب متبادل ويملأ الأماكن الفارغة بصفحات فارغة.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
يحذف الصفحات المحددة من المستند ويحفظ النتيجة في كائن HttpServletResponse.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
يحذف الصفحات المحددة من المستند ويخزن النتيجة في كائن HttpServletResponse.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
يحذف الصفحات المحددة بمصفوفة أرقام من ملف الإدخال، ويحفظها كملف Pdf جديد.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpServletResponse.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف Pdf جديد.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpServletResponse.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
يستخرج الصفحات المحددة بمصفوفة أرقام، ويحفظها كملف PDF جديد.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

مهمل. هذه الخاصية مهملة ولا يمكن استخدامها للسماح برمي الاستثناءات.

**Returns:**
قيمة منطقية

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق.

**Returns:**
قيمة السلسلة

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية.

**Returns:**
قيمة منطقية

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

عدد المستندات المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true.

**Returns:**
قيمة int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse.

**Returns:**
عنصر ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

يحصل على سجل عملية التحويل.

**Returns:**
قيمة السلسلة

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

إذا كانت true، يتم نسخ البنية المنطقية للملف عند تنفيذ الدمج.

**Returns:**
قيمة منطقية

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

إذا كانت true، سيتم نسخ المخططات.

**Returns:**
قيمة منطقية

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا.

**Returns:**
عنصر ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

مصفوفة من المشكلات التي تم مواجهتها عند تنفيذ الدمج.

**Returns:**
مصفوفة PdfFileEditor.CorruptedItem

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

تمثيل لمعالج أحداث التقدم الداخلي الذي يعمل أثناء الدمج ويترجم أحداث الدمج لمراحل الدمج الداخلية إلى كود العميل الخارجي.

**Returns:**
مثيل ConcatenationProgressHandler

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج.

**Returns:**
قيمة منطقية

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

إذا كانت true، سيتم نسخ الإجراءات من المستندات المصدر.

**Returns:**
قيمة منطقية

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج.

**Returns:**
قيمة منطقية

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

يحصل على آخر استثناء حدث.

**Returns:**
كائن java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true.

**Returns:**
قيمة منطقية

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

إذا كانت true، يتم دمج المخططات المتكررة.

**Returns:**
قيمة منطقية

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

يحصل أو يضبط علم التحسين.

**Returns:**
قيمة منطقية

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

يحصل على كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا.

**Returns:**
كائن String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج.

**Returns:**
قيمة منطقية

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة.

**Returns:**
قيمة منطقية

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse.

**Returns:**
كائن SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

احصل على تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عندما يتم دمج النماذج.

**Returns:**
كائن String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
يُدرج المستند في مستند آخر ويخزن النتيجة في كائن الاستجابة.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
يدرج صفحات من ملف آخر في ملف Pdf الإدخال.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
يدرج صفحات من ملف آخر في ملف Pdf الإدخال.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
يُدرج محتويات الملف في الملف المصدر ويخزن النتيجة في كائن HttpServletResponse.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
يدرج صفحات من ملف آخر في ملف Pdf الإدخال.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
يدرج صفحات من ملف آخر في ملف Pdf في موقع معين.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

في بعض الأحيان تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجانب بعضها.

**Returns:**
قيمة منطقية

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة.

**Returns:**
قيمة منطقية

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
ينشئ كتيبًا من InputStream إلى outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
ينشئ كتيبًا من firstInputStream إلى outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
إنشاء كتيب من ملف PDF وتخزينه في HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpServletResponse.

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

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
ينشئ مستندًا N-up ويخزن النتيجة في HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
ينشئ مستندًا N-up ويخزن النتيجة في كائن HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
ينشئ مستندًا N-up ويخزن النتيجة في HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
ينشئ مستندًا N-up ويخزن النتيجة في كائن HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
ينشئ مستند N-Up من firstInputFile إلى outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
ينشئ مستند N-Up من ملف الإدخال إلى outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
ينشئ مستند N-Up من ملفي PDF إلى outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
يغيّر حجم محتويات الصفحات في المستند.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
يغيّر حجم محتويات الصفحات في المستند.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يغيّر حجم محتويات الصفحات في المستند.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

مهمل. هذه الخاصية مهملة ولا يمكن استخدامها للسماح برمي الاستثناءات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

عدد المستندات المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يحدد كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

إذا كانت true، يتم نسخ البنية المنطقية للملف عند تنفيذ الدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

إذا كانت true، سيتم نسخ المخططات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

هذه الخاصية تحدد السلوك عندما تواجه عملية الجمع ملفًا تالفًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
تمثيل لمعالج أحداث التقدم الداخلي الذي يعمل أثناء الدمج ويترجم أحداث الدمج لمراحل الدمج الداخلية إلى كود العميل الخارجي.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

إذا كانت true، سيتم نسخ الإجراءات من المستندات المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

إذا كان صحيحًا فستصبح أسماء الحقول فريدة عندما يتم دمج النماذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

إذا كانت true، يتم دمج المخططات المتكررة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

يحصل أو يضبط علم التحسين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
يحدد كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يحدد خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

في بعض الأحيان تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجانب بعضها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | قيمة منطقية |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
حدد تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
يقسم المستند من البداية إلى الموقع المحدد ويخزن النتيجة في كائن HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
يقسم المستند من الصفحة الأولى إلى الموقع ويحفظ النتيجة في كائنات HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
يقسم من الموقع المحدد، ويحفظ الجزء الخلفي في كائن HttpServletResponse.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream ملف جديد.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
يقسم من الموقع المحدد، ويحفظ الجزء الخلفي في كائن HttpServletResponse.

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
