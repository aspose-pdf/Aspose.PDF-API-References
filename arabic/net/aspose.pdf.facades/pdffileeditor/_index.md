---
title: PdfFileEditor
second_title: Aspose.PDF لمرجع .NET API
description: تنفيذ العمليات باستخدام ملف PDF التسلسل  والتقسيم  واستخراج الصفحات  وإنشاء كتيب  وما إلى ذلك.
type: docs
weight: 2470
url: /ar/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

تنفيذ العمليات باستخدام ملف PDF: التسلسل ، والتقسيم ، واستخراج الصفحات ، وإنشاء كتيب ، وما إلى ذلك.

```csharp
public sealed class PdfFileEditor
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | الحصول على اسم المرفق أو تعيينه عند تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | في حالة التعيين على "صواب" ، يتم إغلاق التدفقات بعد العملية. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | عدد المستندات المتسلسلة قبل إجراء التحديث المتزايد الجديد أثناء التسلسل عند تعيين UseDiskBuffer على "صحيح". |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | الحصول على أو تعيين كيفية تخزين المحتوى عند تخزين نتيجة العملية في كائن HttpResponse. القيمة المحتملة: مضمنة / مرفق . الافتراضي: مضمنة . |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | يحصل على سجل عملية التحويل . |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج في تنسيق الملف المحدد. إذا لم يتم تحديد هذه الخاصية ، فسيتم حفظ الملف بتنسيق PDF الافتراضي بدون تحويل. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | إذا كان هذا صحيحًا ، فسيتم نسخ البنية المنطقية للملف عند إجراء التسلسل. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | إذا كان صحيحًا ، فسيتم نسخ المخططات. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | تحدد هذه الخاصية السلوك عند تلبية عملية التسلسل للملف التالف. القيم المحتملة هي: StopWithError و ConcatenateIgnoringCorrupt. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | مصفوفة المشكلات التي تمت مواجهتها عند إجراء التسلسل. لكل مستند تالف تم تمريره إلى Concatenate () يتم إنشاء إدخال CorruptItem جديد. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | إذا كان هذا صحيحًا ، فسيتم إجراء تحديثات تزايديّة أثناء التسلسل. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | إذا كانت الإجراءات صحيحة سيتم نسخها من المستندات المصدر. القيمة الافتراضية: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | إذا كان صحيحًا ، فسيتم جعل أسماء الحقول فريدة عندما تكون النماذج متسلسلة. ستتم إضافة اللاحقات إلى أسماء الحقول ، ويمكن تحديد قالب اللاحقة في خاصية UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | يحصل على آخر استثناء حدث. يمكن استخدامها للتحقق من سبب الفشل. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | سيتم دمج المحتويات الاختيارية للوثائق المتسلسلة ذات الأسماء المتساوية في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية صحيحة. وإلا ، سيتم حفظ الطبقات ذات الأسماء المتساوية كطبقات مختلفة في المستند الناتج. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | إذا كان صحيحًا ، يتم دمج المخططات التفصيلية المكررة. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | الحصول على علامة التحسين أو تعيينها. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا كانت مجموعة العلامات هذه. هذا يسمح بتقليل حجم الملف الناتج ولكن قد يتسبب في إبطاء التنفيذ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false . |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | يضبط كلمة مرور المالك إذا كان ملف Pdf الخاص بإدخال المصدر مشفرًا. لم يتم تنفيذ هذه الخاصية حتى الآن. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | إذا كان صحيحًا ، يتم تطبيق حقوق المستخدم الخاصة بالمستند الأول على المستند المتسلسل. يتم تجاهل حقوق المستخدم لجميع المستندات الأخرى. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | إذا كان هذا صحيحًا ، فستتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول) خلاف ذلك ، يمكنك الحصول على توقيعات غير صالحة. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | الحصول على أو تعيين خيارات الحفظ عند تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | تنسيق اللاحقة التي تمت إضافتها إلى اسم الحقل لجعلها فريدة عندما تكون النماذج متسلسلة . يجب أن تحتوي هذه السلسلة على٪ NUM٪ سلسلة فرعية سيتم استبدالها بأرقام . على سبيل المثال إذا كان UniqueSuffix = "ABC٪ NUM٪" إذن لـ أسماء الحقول "fieldName" ستكون: fieldNameABC1 ، fieldNameABC2 ، fieldNameABC3 إلخ . |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | إذا تم استخدام هذا الخيار ، فسيتم حفظ المستند الوجهة على القرص بشكل دوري وسيتم تطبيق مزيد من التسلسل عليه كتحديثات تدريجية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | يغير حجم محتويات الصفحة ويضيف هوامش محددة. تم تحديد الهوامش بوحدات المساحة الافتراضية. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | يغير حجم محتويات الصفحة ويضيف هوامش محددة. تم تحديد الهوامش بوحدات المساحة الافتراضية. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | تغيير حجم محتويات الصفحة وإضافة هوامش محددة . يتم تحديد الهوامش بالنسب المئوية من حجم الصفحة الأولي. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | تغيير حجم محتويات الصفحة وإضافة هوامش محددة . يتم تحديد الهوامش بالنسب المئوية من حجم الصفحة الأولي. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | يضيف فواصل الصفحات إلى صفحات المستند. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | يضيف فواصل الصفحات إلى صفحات المستند. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | يضيف فواصل الصفحات إلى صفحات المستند. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | لإلحاق الصفحات ، التي يتم اختيارها من portStream ضمن النطاق من صفحة البداية إلى الصفحة النهائية ، في portStream في نهاية firstInputStream . |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | إلحاق مستندات بالمستند المصدر وحفظ النتيجة في كائن الاستجابة. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | لإلحاق الصفحات ، التي يتم اختيارها من مجموعة من المستندات في portStreams. يتضمن مستند النتيجة firstInputFile وجميع صفحات مستندات portStreams في النطاق من صفحة البداية إلى الصفحة النهائية. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | لإلحاق الصفحات ، التي يتم اختيارها من ملف المنفذ داخل النطاق من صفحة البداية إلى الصفحة النهائية ، في portFile في نهاية firstInputFile . |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | إلحاق مستندات بالمستند المصدر وحفظ النتيجة في كائن HttpResponse . |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | لإلحاق الصفحات التي يتم اختيارها من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles الموجودة في نطاق بدء الصفحة حتى نهاية الصفحة. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | تسلسل المستندات . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | تؤدي الملفات المتسلسلة والمخازن إلى كائن HttpResponse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | تسلسل الملفات |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | يربط الملفات ويحفظ reslt في كائن HttpResposnse . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | يربط الملفات في ملف واحد. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | يربط بين ملفين. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | يربط بين ملفين. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | يدمج مستندين من ملفات PDF في مستند Pdf جديد مع الصفحات بطرق بديلة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند 1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند 2 على 3 صفحات: p1 '، p2'، p3 '. دمج ملفي PDF سينتج المستند الناتج بالصفحات: p1، p1'، p2، p2 '، p3، p3'، p4، blankpage، p5، blankpage . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | يدمج مستندين من ملفات PDF في مستند Pdf جديد مع الصفحات بطرق بديلة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند 1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند 2 على 3 صفحات: p1 '، p2'، p3 '. دمج ملفي PDF سينتج المستند الناتج بالصفحات: p1، p1'، p2، p2 '، p3، p3'، p4، blankpage، p5، blankpage . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | حذف الصفحات المحددة من المستند وحفظ النتيجة في كائن HttpResponse . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | حذف الصفحات المحددة من المستند وتخزين النتائج في كائن HttpResponse . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | استخراج الصفحات المحددة من الملف المصدر وتخزين النتائج في كائن HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | لاستخراج الصفحات المحددة بواسطة مصفوفة الأرقام ، وحفظها كملف Pdf جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | استخراج الصفحات المحددة من الملف المصدر وتخزين النتائج في كائن HttpResponse . |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | لاستخراج الصفحات المحددة بواسطة مصفوفة الأرقام ، وحفظها كملف PDF جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | استخراج الصفحات من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | استخراج الصفحات من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | إدراج المستند في مستند آخر وتخزين النتائج في كائن استجابة. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | إدراج محتويات الملف في الملف المصدر وتخزين النتائج في كائن HttpResponse . |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | يقوم بإدراج صفحات من ملف آخر في ملف Pdf في موضع ما. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | يجعل كتيب من InputStream لإخراج البث . |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | يجعل كتيب من ملف الإدخال إلى ملف الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | يجعل الكتيب من الملف المصدر والمخازن ينتج عنه HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | يجعل كتيب من دفق الإدخال وحفظ النتيجة في دفق الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | يجعل الكتيب من ملف الإدخال إلى ملف الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | إنشاء كتيب مخصص من أول إدخال إلى بث الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | إنشاء كتيب مخصص من ملف الإدخال الأول إلى ملف الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | إنشاء كتيب من ملف PDF وتخزينه في HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | يجعل الكتيب من أول InputStream إلى outputStream . |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse . |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | إنشاء كتيب مخصص من ملف الإدخال الأول إلى ملف الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | يجعل مستند N-Up من دفقتي PDF للإدخال إلى outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | يجعل مستند N-Up من تدفقات PDF متعددة المدخلات إلى outputStream . ستحتوي كل صفحة من تدفق الإخراج على صفحات متعددة ، والتي يتم دمجها مع صفحات في تدفقات الإدخال لنفس رقم الصفحة. الصفحات المتعددة المكدسة أفقيًا إذا كان الجانب الآخر صحيحًا ومكدسة عموديًا إذا كان العرض الجانبي خاطئًا. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | يجعل مستند N-Up من ملفي PDF للإدخال إلى ملف الإخراج. ستحتوي كل صفحة من ملف الإخراج على صفحتين ، صفحة واحدة من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. الصفحتان مكدمتان أفقيًا. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | يجعل مستند N-Up من ملفات PDF متعددة المدخلات إلى ملف الإخراج. ستحتوي كل صفحة من ملف الإخراج على صفحات متعددة ، والتي يتم دمجها مع الصفحات في ملفات الإدخال لنفس رقم الصفحة. الصفحات المتعددة المكدسة أفقيًا إذا كان الجانب الآخر صحيحًا ومكدسة عموديًا إذا كان العرض الجانبي خاطئًا. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | يجعل المستندات والمخازن N-up تؤدي إلى HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | يجعل مستند N-Up من دفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | يجعل مستند N-up والمخازن ينتج عنه HttpResponse . |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | يجعل مستند N-Up من firstInputFile إلى ملف الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse . |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | يجعل مستند N-Up من دفق الإدخال الأول إلى تدفق الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse . |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | يجعل مستند N-Up من ملف الإدخال إلى ملف الإخراج. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | يغير حجم صفحات المستند. تتم إضافة هوامش فارغة حول الصفحة المتقلصة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | يغير حجم صفحات المستند. تتم إضافة هوامش فارغة حول الصفحة المتقلصة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | تغيير حجم محتويات صفحات المستند. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | يغير حجم محتويات صفحات الوثيقة. يتقلص محتويات الصفحة ويضيف هوامش . يتم تحديد الحجم الجديد للمحتويات في وحدات المساحة الافتراضية. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | يغير حجم محتويات صفحات الوثيقة. يتقلص محتويات الصفحة ويضيف هوامش . يتم تحديد الحجم الجديد للمحتويات في وحدات المساحة الافتراضية. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | تغيير حجم محتويات صفحات المستند. تقليص محتويات الصفحة وإضافة هوامش . يتم تحديد حجم محتويات جديد بالنسب المئوية. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | تغيير حجم محتويات صفحات المستند. تقليص محتويات الصفحة وإضافة هوامش . يتم تحديد حجم محتويات جديد بالنسب المئوية. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | يقسم المستند من البداية إلى الموقع المحدد ويخزن النتيجة في كائن HttpResponse . |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | ينقسم من البداية إلى الموقع المحدد ، ويحفظ الجزء الأمامي في تيار الإخراج. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | يقسم المستند من الصفحة الأولى إلى الموقع ويحفظ النتيجة في كائنات HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | تقسيم ملف Pdf من الصفحة الأولى إلى الموقع المحدد ، ويحفظ الجزء الأمامي كملف جديد. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | يقسم ملف Pdf إلى عدة مستندات ، ويمكن أن تكون المستندات من صفحة واحدة أو متعددة الصفحات. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | يقسم ملف Pdf إلى عدة مستندات ، ويمكن أن تكون المستندات من صفحة واحدة أو متعددة الصفحات. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | ينقسم من الموقع المحدد ، ويحفظ الجزء الخلفي في كائن HttpResponse . |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | ينقسم عن الموقع المحدد ، ويحفظ الجزء الخلفي كملف جديد. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | ينقسم من الموقع المحدد ، ويحفظ الجزء الخلفي في كائن HttpResponse . |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | ينقسم عن الموقع ويحفظ الجزء الخلفي كملف جديد. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | يقسم ملف Pdf إلى مستندات من صفحة واحدة. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | يقسم ملف PDF إلى مستندات من صفحة واحدة. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | قم بتقسيم ملف Pdf إلى مستندات من صفحة واحدة وحفظه في المسار المحدد. المسار محدد حسب اسم الحقل temaplate . |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | قم بتقسيم ملف Pdf إلى مستندات من صفحة واحدة وحفظه في المسار المحدد. المسار محدد حسب اسم الحقل temaplate . |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | إلحاق مستندات بالمستند المصدر وحفظ النتيجة في كائن الاستجابة. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | لإلحاق الصفحات ، التي يتم اختيارها من مجموعة من المستندات في portStreams. يتضمن مستند النتيجة firstInputFile وجميع صفحات مستندات portStreams في النطاق من صفحة البداية إلى الصفحة النهائية. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | إلحاق مستندات بالمستند المصدر وحفظ النتيجة في كائن HttpResponse . |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | لإلحاق الصفحات التي يتم اختيارها من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles الموجودة في نطاق بدء الصفحة حتى نهاية الصفحة. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | تسلسل المستندات . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | تؤدي الملفات المتسلسلة والمخازن إلى كائن HttpResponse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | تسلسل الملفات |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | يربط الملفات ويحفظ reslt في كائن HttpResposnse . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | يربط الملفات في ملف واحد. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | يربط بين ملفين. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | يدمج مستندين من ملفات PDF في مستند Pdf جديد مع الصفحات بطرق بديلة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند 1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند 2 على 3 صفحات: p1 '، p2'، p3 '. دمج ملفي PDF سينتج المستند الناتج بالصفحات: p1، p1'، p2، p2 '، p3، p3'، p4، blankpage، p5، blankpage . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | يدمج مستندين من ملفات PDF في مستند Pdf جديد مع الصفحات بطرق بديلة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: يحتوي المستند 1 على 5 صفحات: p1، p2، p3، p4، p5. يحتوي المستند 2 على 3 صفحات: p1 '، p2'، p3 '. دمج ملفي PDF سينتج المستند الناتج بالصفحات: p1، p1'، p2، p2 '، p3، p3'، p4، blankpage، p5، blankpage . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | حذف الصفحات المحددة من المستند وحفظ النتيجة في كائن HttpResponse . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | حذف الصفحات المحددة من المستند وتخزين النتائج في كائن HttpResponse . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | حذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | استخراج الصفحات المحددة من الملف المصدر وتخزين النتائج في كائن HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | لاستخراج الصفحات المحددة بواسطة مصفوفة الأرقام ، وحفظها كملف Pdf جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | استخراج الصفحات المحددة من الملف المصدر وتخزين النتائج في كائن HttpResponse . |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | لاستخراج الصفحات المحددة بواسطة مصفوفة الأرقام ، وحفظها كملف PDF جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | استخراج الصفحات من ملف الإدخال ، وحفظها كملف Pdf جديد. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | إدراج المستند في مستند آخر وتخزين النتائج في كائن استجابة. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | إدراج محتويات الملف في الملف المصدر وتخزين النتائج في كائن HttpResponse . |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | إدراج صفحات من ملف آخر في ملف Pdf الخاص بالإدخال. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | يجعل كتيب من InputStream لإخراج البث . |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | يجعل الكتيب من ملف الإدخال إلى ملف الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | يجعل الكتيب من الملف المصدر والمخازن ينتج عنه HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | يجعل كتيب من دفق الإدخال وحفظ النتيجة في دفق الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | يجعل الكتيب من ملف الإدخال إلى ملف الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | إنشاء كتيب مخصص من أول إدخال إلى بث الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | إنشاء كتيب مخصص من ملف الإدخال الأول إلى ملف الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | إنشاء كتيب من ملف PDF وتخزينه في HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | يجعل الكتيب من أول InputStream إلى outputStream . |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | يجعل الكتيب من الملف المصدر والمخازن ينتج عنه كائنات HttpResponse . |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | إنشاء كتيب مخصص من ملف الإدخال الأول إلى ملف الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | يجعل مستند N-Up من دفقتي PDF للإدخال إلى outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | يجعل مستند N-Up من تدفقات PDF متعددة المدخلات إلى outputStream . ستحتوي كل صفحة من تدفق الإخراج على صفحات متعددة ، والتي يتم دمجها مع صفحات في تدفقات الإدخال لنفس رقم الصفحة. الصفحات المتعددة المكدسة أفقيًا إذا كان الجانب الآخر صحيحًا ومكدسة عموديًا إذا كان العرض الجانبي خاطئًا. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | يجعل مستند N-Up من ملفي PDF للإدخال إلى ملف الإخراج. ستحتوي كل صفحة من ملف الإخراج على صفحتين ، صفحة واحدة من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. الصفحتان مكدمتان أفقيًا. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | يجعل مستند N-Up من ملفات PDF متعددة المدخلات إلى ملف الإخراج. ستحتوي كل صفحة من ملف الإخراج على صفحات متعددة ، والتي يتم دمجها مع الصفحات في ملفات الإدخال لنفس رقم الصفحة. الصفحات المتعددة المكدسة أفقيًا إذا كان الجانب الآخر صحيحًا ومكدسة عموديًا إذا كان العرض الجانبي خاطئًا. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | يجعل المستندات والمخازن N-up تؤدي إلى HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | يجعل مستند N-Up من دفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | يجعل مستند N-up والمخازن ينتج عنه HttpResponse . |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | يجعل مستند N-Up من firstInputFile إلى ملف الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse . |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | يجعل مستند N-Up من دفق الإدخال الأول إلى تدفق الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | جعل مستند N-up والمخازن ينتج عنه كائن HttpResponse . |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | يجعل مستند N-Up من ملف الإدخال إلى ملف الإخراج. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | تغيير حجم محتويات صفحات المستند. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | يغير حجم محتويات الصفحات في المستند. إذا تم تقليص الصفحة ، تتم إضافة هوامش فارغة حول الصفحة. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | يغير حجم محتويات صفحات الوثيقة. يتقلص محتويات الصفحة ويضيف هوامش . يتم تحديد الحجم الجديد للمحتويات في وحدات المساحة الافتراضية. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | يقسم المستند من البداية إلى الموقع المحدد ويخزن النتيجة في كائن HttpResponse . |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | ينقسم من البداية إلى الموقع المحدد ، ويحفظ الجزء الأمامي في تيار الإخراج. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | يقسم المستند من الصفحة الأولى إلى الموقع ويحفظ النتيجة في كائنات HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | تقسيم ملف Pdf من الصفحة الأولى إلى الموقع المحدد ، ويحفظ الجزء الأمامي كملف جديد. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | ينقسم من الموقع المحدد ، ويحفظ الجزء الخلفي في كائن HttpResponse . |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | ينقسم عن الموقع المحدد ، ويحفظ الجزء الخلفي كملف جديد. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | ينقسم من الموقع المحدد ، ويحفظ الجزء الخلفي في كائن HttpResponse . |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | ينقسم عن الموقع ويحفظ الجزء الخلفي كملف جديد. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | تم تنفيذ الإجراء عند استيفاء ملف تالف في عملية التسلسل. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | فئة لتحديد معلمات تغيير حجم الصفحة. السماح بتعيين المعلمات التالية: حجم صفحة النتائج (العرض ، الارتفاع) في وحدات المساحة الافتراضية أو بالنسب المئوية لحجم الصفحات الأولية الهوامش اليسرى والعلوية والسفلية واليمنى بوحدات المساحة الافتراضية أو بالنسب المئوية من حجم الصفحة الأولي قد تُترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من باقي حجم الصفحة بعد حساب القيم المحددة بوضوح. على سبيل المثال: إذا كان عرض الصفحة = 100 وعرض الصفحة الجديد المحدد 60 وحدة ، فسيتم حساب الهوامش اليمنى واليسرى تلقائيًا: (100-60) / 2 = 15. هذه الفئة مستخدمة في طريقة ResizeContents. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | قيمة الهامش أو حجم المحتوى المحدد بالنسب المئوية لوحدات المساحة الافتراضية . هذه الفئة مستخدمة في ContentsResizeParameters. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | فئة توفر معلومات حول الملفات التالفة في وقت التسلسل. |
| class [PageBreak](pdffileeditor.pagebreak) | بيانات موضع فاصل الصفحة . |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
