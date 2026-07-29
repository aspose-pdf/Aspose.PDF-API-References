---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تنفّذ عمليات على ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيّب، إلخ."
type: docs
weight: 410
url: /ar/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

تنفّذ عمليات على ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيّب، إلخ.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | منشئ PdfFileEditor. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بوحدات المساحة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بوحدات المساحة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بالنسبة المئوية من حجم الصفحة الأولي. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بالنسبة المئوية من حجم الصفحة الأولي. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | يضيف فواصل صفحات إلى صفحات المستند. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> يضيف الصفحات التي يتم اختيارها من مصفوفة المستندات في portStreams. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portStreams في النطاق من startPage إلى endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> يضيف الصفحات التي يتم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> يضيف الصفحات التي يتم اختيارها من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles في النطاق من startPage إلى endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> يضيف الصفحات التي يتم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | يجمع المستندات. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> يجمع الملفات </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> يدمج مستندين Pdf في مستند Pdf جديد مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سينتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> يجمع ملفين. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> يجمع الملفات في ملف واحد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> يجمع ملفين. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> يدمج مستندين Pdf في مستند Pdf جديد مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سينتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> إذا تم تعيينها إلى true، تُرمى الاستثناءات عند حدوث خطأ. وإلا لا تُرمى الاستثناءات وتُعيد الطرق false إذا فشلت. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | إذا تم تعيينها إلى true، تُغلق التدفقات بعد العملية. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | عدد المستندات المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true. |
| [getContentDisposition](#getContentDisposition--) | يحصل على طريقة تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [getConversionLog](#getConversionLog--) | يحصل على سجل عملية التحويل. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | إذا كانت true، يتم نسخ البنية المنطقية للملف عند تنفيذ الدمج. |
| [getCopyOutlines](#getCopyOutlines--) | إذا كانت true، سيتم نسخ المخططات. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | تحدد هذه الخاصية السلوك عندما تواجه عملية الدمج ملفًا معطوبًا. القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> مصفوفة المشاكل التي تم مواجهتها عند تنفيذ الدمج. لكل مستند معطوب تم تمريره إلى دالة Concatenate() يتم إنشاء إدخال CorruptedItem جديد. يمكن استخدام هذه الخاصية فقط عندما تكون CorruptedFileAction هي ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | تمثيل لمعالج أحداث التقدم الداخلي الذي يعمل أثناء الدمج ويترجم أحداث الدمج لمراحل الدمج الداخلية إلى كود العميل الخارجي. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج. |
| [getKeepActions](#getKeepActions--) | إذا كانت true، سيتم نسخ الإجراءات من المستندات المصدر. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | إذا كانت true، سيتم جعل أسماء الحقول فريدة عند دمج النماذج. ستُضاف لاحقات إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في الخاصية UniqueSuffix. |
| [getLastException](#getLastException--) | يحصل على آخر استثناء حدث. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | إذا كانت true، يتم دمج المخططات المتكررة. |
| [getOptimizeSize](#getOptimizeSize--) | يحصل أو يضبط علم التحسين. |
| [getOwnerPassword](#getOwnerPassword--) | يحصل على كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا. هذه الخاصية لم تُنفذ بعد. |
| [getPreserveUserRights](#getPreserveUserRights--) | إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج. |
| [getRemoveSignatures](#getRemoveSignatures--) | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة. |
| [getSaveOptions](#getSaveOptions--) | يحصل أو يعيّن خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. القيمة الافتراضية: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | احصل على تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. يجب أن يحتوي هذا النص على الجزء الفرعي %NUM% الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1, fieldNameABC2, fieldNameABC3 إلخ. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> يدرج صفحات من ملف آخر إلى ملف PDF الإدخال. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> يدرج صفحات من ملف آخر إلى ملف PDF الإدخال. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> يدرج صفحات من ملف آخر إلى ملف PDF الإدخال. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> يدرج صفحات من ملف آخر إلى ملف PDF في موضع معين. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | في بعض الأحيان تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجانب بعضها. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> ينشئ كتيبًا من InputStream إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> ينشئ كتيبًا من firstInputStream إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> ينشئ كتيبًا من inputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> ينشئ مستند N‑Up من تدفقات PDF المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال ذات رقم الصفحة نفسه. تُرص الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرص عمودياً إذا كان isSidewise خطأ. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> ينشئ مستند N‑Up من تدفقَي PDF الإدخال إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> ينشئ مستند N‑Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> ينشئ مستند N‑Up من تدفق الإدخال الأول إلى تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> ينشئ مستند N‑Up من ملفات PDF المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال ذات رقم الصفحة نفسه. تُرص الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرص عمودياً إذا كان isSidewise خطأ. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> ينشئ مستند N‑Up من firstInputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> ينشئ مستند N‑Up من ملف الإدخال إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> ينشئ مستند N‑Up من ملفي PDF الإدخال إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، إحداهما من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. تُرص الصفحتان أفقياً. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم محتويات صفحات المستند. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> يغيّر حجم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //إعادة تحجيم جميع صفحات المستند null, //العرض الجديد للمحتويات = 200 200, //الارتفاع الجديد للمحتويات = 300 300); // المنطقة المتبقية من الصفحة ستكون فارغة </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يغيّر حجم محتويات الصفحات في المستند. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> يغيّر حجم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد حجم المحتويات الجديد بالنسبة المئوية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //إعادة تحجيم جميع صفحات المستند null, //العرض الجديد للمحتويات = 60% من الحجم الأصلي 60, //الارتفاع الجديد للمحتويات = 60% من الحجم الأصلي 60); // المنطقة المتبقية من الصفحة ستكون فارغة (هوامش الصفحة). حجم الهوامش اليسرى واليمنى هو (100% - 60%) / 2 = 20% // نفس الشيء للهوامش العلوية والسفلية. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> يغيّر حجم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد حجم المحتويات الجديد بالنسبة المئوية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //إعادة تحجيم جميع صفحات المستند null, //العرض الجديد للمحتويات = 60% من الحجم الأصلي 60, //الارتفاع الجديد للمحتويات = 60% من الحجم الأصلي 60); // المنطقة المتبقية من الصفحة ستكون فارغة (هوامش الصفحة). حجم الهوامش اليسرى واليمنى هو (100% - 60%) / 2 = 20% // نفس الشيء للهوامش العلوية والسفلية. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | يعيد تحجيم صفحات المستند. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> إذا تم تعيينها إلى true، يتم إلقاء الاستثناءات إذا حدث خطأ. وإلا لا يتم إلقاء الاستثناءات وتعيد الطرق false إذا فشلت. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> إذا تم تعيينها إلى true، يتم إغلاق التدفقات بعد العملية. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | عدد المستندات المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | إذا كانت true، يتم نسخ البنية المنطقية للملف عند تنفيذ الدمج. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | إذا كانت true، سيتم نسخ المخططات. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | تحدد هذه الخاصية السلوك عندما تواجه عملية الدمج ملفًا معطوبًا. القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | تمثيل لمعالج أحداث التقدم الداخلي الذي يعمل أثناء الدمج ويترجم أحداث الدمج لمراحل الدمج الداخلية إلى كود العميل الخارجي. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | إذا كانت true، تُجرى تحديثات تدريجية أثناء الدمج. |
| [setKeepActions](#setKeepActions-boolean-) | إذا كانت true، سيتم نسخ الإجراءات من المستندات المصدر. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | إذا كانت true، سيتم جعل أسماء الحقول فريدة عند دمج النماذج. ستُضاف لاحقات إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في الخاصية UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | إذا كانت true، يتم دمج المخططات المتكررة. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | يحصل أو يضبط علم التحسين. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | يضبط كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا. هذه الخاصية غير مطبقة بعد. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. القيمة الافتراضية: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | في بعض الأحيان تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجانب بعضها. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> اضبط تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعلها فريدةً عند دمج النماذج. يجب أن تحتوي هذه السلسلة على الجزء الفرعي %NUM% الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1, fieldNameABC2, fieldNameABC3 إلخ. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> التدفقات لا تُغلق بعد هذه العملية. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كدفق ملف جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> التدفقات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد. |
| [splitToPages](#splitToPages-java.lang.String-) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

منشئ PdfFileEditor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بوحدات المساحة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بوحدات المساحة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بالنسبة المئوية من حجم الصفحة الأولي. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. يتم تحديد الهوامش بالنسبة المئوية من حجم الصفحة الأولي. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
يضيف فواصل صفحات إلى صفحات المستند.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> يضيف الصفحات التي يتم اختيارها من مصفوفة المستندات في portStreams. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portStreams في النطاق من startPage إلى endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> يضيف الصفحات التي يتم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> يضيف الصفحات التي يتم اختيارها من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles في النطاق من startPage إلى endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> يضيف الصفحات التي يتم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
يجمع المستندات.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> يجمع الملفات </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> يدمج مستندين Pdf في مستند Pdf جديد مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سينتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> يجمع ملفين. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> يجمع الملفات في ملف واحد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> يجمع ملفين. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> يدمج مستندين Pdf في مستند Pdf جديد مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سينتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> إذا تم تعيينها إلى true، تُرمى الاستثناءات عند حدوث خطأ. وإلا لا تُرمى الاستثناءات وتُعيد الطرق false إذا فشلت. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
قيمة منطقية @deprecated هذه الخاصية مهجورة ولا يمكن استخدامها للسماح برمي الاستثناءات.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق.

**Returns:**
قيمة سلسلة

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

يحصل على طريقة تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

**Returns:**
عنصر ContentDisposition @see ContentDisposition

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

تحدد هذه الخاصية السلوك عندما تواجه عملية الدمج ملفًا معطوبًا. القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted.

**Returns:**
عنصر ConcatenateCorruptedFileAction @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> مصفوفة المشاكل التي تم مواجهتها عند تنفيذ الدمج. لكل مستند معطوب تم تمريره إلى دالة Concatenate() يتم إنشاء إدخال CorruptedItem جديد. يمكن استخدام هذه الخاصية فقط عندما تكون CorruptedFileAction هي ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
مصفوفة من PdfFileEditor.CorruptedItem

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

إذا كانت true، سيتم جعل أسماء الحقول فريدة عند دمج النماذج. ستُضاف لاحقات إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في الخاصية UniqueSuffix.

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

يحصل على كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا. هذه الخاصية لم تُنفذ بعد.

**Returns:**
قيمة سلسلة

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

إذا كان صحيحًا، يتم تطبيق حقوق المستخدم للمستند الأول على المستند المدمج.

**Returns:**
قيمة منطقية

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة.

**Returns:**
قيمة منطقية

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

يحصل أو يعيّن خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. القيمة الافتراضية: PdfSaveOptions.

**Returns:**
كائن SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

احصل على تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. يجب أن يحتوي هذا النص على الجزء الفرعي %NUM% الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1, fieldNameABC2, fieldNameABC3 إلخ.

**Returns:**
قيمة سلسلة

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> يدرج صفحات من ملف آخر إلى ملف PDF الإدخال. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> يدرج صفحات من ملف آخر إلى ملف PDF الإدخال. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> يدرج صفحات من ملف آخر إلى ملف PDF الإدخال. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> يدرج صفحات من ملف آخر إلى ملف PDF في موضع معين. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> ينشئ كتيبًا من InputStream إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> ينشئ كتيبًا من firstInputStream إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> ينشئ كتيبًا من inputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> ينشئ مستند N‑Up من تدفقات PDF المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال ذات رقم الصفحة نفسه. تُرص الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرص عمودياً إذا كان isSidewise خطأ. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> ينشئ مستند N‑Up من تدفقَي PDF الإدخال إلى outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> ينشئ مستند N‑Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> ينشئ مستند N‑Up من تدفق الإدخال الأول إلى تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> ينشئ مستند N‑Up من ملفات PDF المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال ذات رقم الصفحة نفسه. تُرص الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرص عمودياً إذا كان isSidewise خطأ. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> ينشئ مستند N‑Up من firstInputFile إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> ينشئ مستند N‑Up من ملف الإدخال إلى outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> ينشئ مستند N‑Up من ملفي PDF الإدخال إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، إحداهما من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. تُرص الصفحتان أفقياً. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم محتويات صفحات المستند.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> يغيّر حجم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //إعادة تحجيم جميع صفحات المستند null, //العرض الجديد للمحتويات = 200 200, //الارتفاع الجديد للمحتويات = 300 300); // المنطقة المتبقية من الصفحة ستكون فارغة </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يغيّر حجم محتويات الصفحات في المستند.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> يغيّر حجم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد حجم المحتويات الجديد بالنسبة المئوية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //إعادة تحجيم جميع صفحات المستند null, //العرض الجديد للمحتويات = 60% من الحجم الأصلي 60, //الارتفاع الجديد للمحتويات = 60% من الحجم الأصلي 60); // المنطقة المتبقية من الصفحة ستكون فارغة (هوامش الصفحة). حجم الهوامش اليسرى واليمنى هو (100% - 60%) / 2 = 20% // نفس الشيء للهوامش العلوية والسفلية. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> يغيّر حجم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يتم تحديد حجم المحتويات الجديد بالنسبة المئوية. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //إعادة تحجيم جميع صفحات المستند null, //العرض الجديد للمحتويات = 60% من الحجم الأصلي 60, //الارتفاع الجديد للمحتويات = 60% من الحجم الأصلي 60); // المنطقة المتبقية من الصفحة ستكون فارغة (هوامش الصفحة). حجم الهوامش اليسرى واليمنى هو (100% - 60%) / 2 = 20% // نفس الشيء للهوامش العلوية والسفلية. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
يعيد تحجيم صفحات المستند.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> إذا تم تعيينها إلى true، يتم إلقاء الاستثناءات إذا حدث خطأ. وإلا لا يتم إلقاء الاستثناءات وتعيد الطرق false إذا فشلت. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated هذه الخاصية مهجورة ولا يمكن استخدامها للسماح برمي الاستثناءات. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpServletResponse كمرفق.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> إذا تم تعيينها إلى true، يتم إغلاق التدفقات بعد العملية. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpServletResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل.

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

تحدد هذه الخاصية السلوك عندما تواجه عملية الدمج ملفًا معطوبًا. القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عددية @see ConcatenateCorruptedFileAction |

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

إذا كانت true، سيتم جعل أسماء الحقول فريدة عند دمج النماذج. ستُضاف لاحقات إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في الخاصية UniqueSuffix.

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
يضبط كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا. هذه الخاصية غير مطبقة بعد.

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
public final void setRemoveSignatures(boolean value)
```

إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول); وإلا، قد تحصل على توقيعات غير صالحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpServletResponse. القيمة الافتراضية: PdfSaveOptions.

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
<p> اضبط تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعلها فريدةً عند دمج النماذج. يجب أن تحتوي هذه السلسلة على الجزء الفرعي %NUM% الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1, fieldNameABC2, fieldNameABC3 إلخ. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

إذا تم استخدام هذا الخيار، فسيتم حفظ المستند الهدف على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> التدفقات لا تُغلق بعد هذه العملية.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
يقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كدفق ملف جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> التدفقات لا تُغلق بعد هذه العملية ما لم يتم تحديد CloseConcatedStreams.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
يقسم ملف PDF إلى مستندات صفحة واحدة.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد.

### splitToPages {#splitToPages-java.lang.String-}
يقسم ملف PDF إلى مستندات صفحة واحدة.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
قسّم ملف Pdf إلى مستندات صفحة واحدة واحفظه في المسار المحدد.
