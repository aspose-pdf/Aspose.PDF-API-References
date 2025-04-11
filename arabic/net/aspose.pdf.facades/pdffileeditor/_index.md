---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfFileEditor. تنفذ العمليات المتعلقة بدمج ملفات PDF وتقسيمها واستخراج الصفحات وصنع كتيبات وما إلى ذلك
type: docs
weight: 4460
url: /ar/net/aspose.pdf.facades/pdffileeditor/
---
## فئة PdfFileEditor

تنفذ العمليات المتعلقة بملف PDF: الدمج، التقسيم، استخراج الصفحات، صنع كتيب، إلخ.

```csharp
public sealed class PdfFileEditor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | إذا تم تعيينه على true، يتم إغلاق التدفقات بعد العملية. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | عدد الوثائق المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer على true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | يحصل على سجل عملية التحويل. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بالتنسيق الافتراضي لـ PDF دون تحويل. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | إذا كان true، يتم نسخ الهيكل المنطقي للملف عند إجراء الدمج. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | إذا كان true، سيتم نسخ المخططات. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | تحدد هذه الخاصية السلوك عند مواجهة ملف تالف أثناء عملية الدمج. القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | مصفوفة من المشكلات التي تمت مواجهتها عند إجراء الدمج. لكل وثيقة تالفة من الممررة إلى دالة Concatenate() يتم إنشاء إدخال جديد من نوع CorruptedItem. يمكن استخدام هذه الخاصية فقط عندما تكون CorruptedFileAction هي ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | إذا كان true، يتم إجراء تحديثات تدريجية أثناء الدمج. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | إذا كان true، سيتم نسخ الإجراءات من الوثائق المصدر. القيمة الافتراضية: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | إذا كان true، سيتم جعل أسماء الحقول فريدة عند دمج النماذج. سيتم إضافة لواحق إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في خاصية UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | يحصل على آخر استثناء حدث. يمكن استخدامه للتحقق من سبب الفشل. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | المحتويات الاختيارية للوثائق المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في الوثيقة الناتجة إذا كانت هذه الخاصية true. خلاف ذلك، سيتم حفظ الطبقات ذات الأسماء المتساوية كطبقات مختلفة في الوثيقة الناتجة. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | إذا كان true، يتم دمج المخططات المكررة. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | يحصل على أو يحدد علامة التحسين. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. يسمح ذلك بتقليل حجم الملف الناتج ولكن قد يتسبب في تنفيذ أبطأ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | يحدد كلمة مرور المالك إذا كان ملف PDF المدخل مشفرًا. لم يتم تنفيذ هذه الخاصية بعد. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | إذا كان true، يتم تطبيق حقوق المستخدم للوثيقة الأولى على الوثيقة المدمجة. يتم تجاهل حقوق المستخدم لجميع الوثائق الأخرى. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | إذا كان true، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول)؛ خلاف ذلك، يمكنك الحصول على توقيعات غير صالحة. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | تنسيق اللاحقة التي تضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. يجب أن تحتوي هذه السلسلة على جزء فرعي %NUM% سيتم استبداله بالأرقام. على سبيل المثال، إذا كانت UniqueSuffix = "ABC%NUM%"، فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1، fieldNameABC2، fieldNameABC3، إلخ. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | إذا تم استخدام هذا الخيار، سيتم حفظ الوثيقة الوجهة على القرص بشكل دوري وسيتم تطبيق الدمج اللاحق عليها كتحديثات تدريجية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | يعيد حجم محتويات الصفحة ويضيف الهوامش المحددة. يتم تحديد الهوامش بوحدات الفضاء الافتراضية. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | يعيد حجم محتويات الصفحة ويضيف الهوامش المحددة. يتم تحديد الهوامش بوحدات الفضاء الافتراضية. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | يعيد حجم محتويات الصفحة ويضيف الهوامش المحددة. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأولية. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | يعيد حجم محتويات الصفحة ويضيف الهوامش المحددة. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأولية. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | يضيف فواصل صفحات إلى صفحات الوثيقة. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | يضيف فواصل صفحات إلى صفحات الوثيقة. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | يضيف فواصل صفحات إلى صفحات الوثيقة. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | يضيف الصفحات، التي تم اختيارها من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | يضيف الصفحات، التي تم اختيارها من مصفوفة الوثائق في portStreams. تتضمن الوثيقة الناتجة firstInputFile وجميع صفحات وثائق portStreams في النطاق من startPage إلى endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | يضيف الصفحات، التي تم اختيارها من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | يضيف الصفحات، التي تم اختيارها من وثائق portFiles. تتضمن الوثيقة الناتجة firstInputFile وجميع صفحات وثائق portFiles في النطاق من startPage إلى endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | يدمج الوثائق. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | يدمج الملفات |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | يدمج الملفات في ملف واحد. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | يدمج ملفين. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | يدمج ملفين. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | يدمج وثيقتين PDF في وثيقة PDF جديدة مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: تحتوي الوثيقة1 على 5 صفحات: p1، p2، p3، p4، p5. تحتوي الوثيقة2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج وثيقتي PDF إلى إنتاج الوثيقة الناتجة مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | يدمج وثيقتين PDF في وثيقة PDF جديدة مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: تحتوي الوثيقة1 على 5 صفحات: p1، p2، p3، p4، p5. تحتوي الوثيقة2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج وثيقتي PDF إلى إنتاج الوثيقة الناتجة مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | يحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | يحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | يستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | يستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | يُدخل الصفحات من ملف آخر في ملف PDF الإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | يُدخل الصفحات من ملف آخر في ملف PDF الإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | يُدخل الصفحات من ملف آخر في ملف PDF الإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | يُدخل الصفحات من ملف آخر في ملف PDF في موضع. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | يصنع كتيب من InputStream إلى outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | يصنع كتيب من ملف الإدخال إلى ملف الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | يصنع كتيب من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | يصنع كتيب من inputFile إلى outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | يصنع كتيب مخصص من InputStream الأول إلى outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | يصنع كتيب مخصص من firstInputFile إلى outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | يصنع كتيب من InputStream الأول إلى outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | يصنع كتيب مخصص من firstInputFile إلى outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | يصنع وثيقة N-Up من تدفقات PDF المدخلة إلى outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | يصنع وثيقة N-Up من تدفقات PDF المدخلة المتعددة إلى outputStream. ستحتوي كل صفحة من outputStream على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال بنفس رقم الصفحة. تتراكم الصفحات المتعددة أفقيًا إذا كانت isSidewise true وتتراكم عموديًا إذا كانت isSidewise false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | يصنع وثيقة N-Up من ملفي PDF المدخلين إلى outputFile. ستحتوي كل صفحة من outputFile على صفحتين، صفحة واحدة من ملف الإدخال الأول وأخرى من ملف الإدخال الثاني. تتراكم الصفحتان أفقيًا. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | يصنع وثيقة N-Up من ملفات PDF المدخلة المتعددة إلى outputFile. ستحتوي كل صفحة من outputFile على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال بنفس رقم الصفحة. تتراكم الصفحات المتعددة أفقيًا إذا كانت isSidewise true وتتراكم عموديًا إذا كانت isSidewise false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | يصنع وثيقة N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | يصنع وثيقة N-Up من firstInputFile إلى outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | يصنع وثيقة N-Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | يصنع وثيقة N-Up من ملف الإدخال إلى outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | يعيد حجم صفحات الوثيقة. تتم إضافة هوامش فارغة حول الصفحة المتقلصة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | يعيد حجم صفحات الوثيقة. تتم إضافة هوامش فارغة حول الصفحة المتقلصة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | يعيد حجم محتويات صفحات الوثيقة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | يعيد حجم محتويات الصفحات في الوثيقة. إذا تم تقليص الصفحة، تتم إضافة هوامش فارغة حول الصفحة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | يعيد حجم محتويات صفحات الوثيقة. يتم تقليص محتويات الصفحة وإضافة هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | يعيد حجم محتويات صفحات الوثيقة. يتم تقليص محتويات الصفحة وإضافة هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | يعيد حجم محتويات صفحات الوثيقة. يتم تقليص محتويات الصفحة وإضافة هوامش. يتم تحديد حجم المحتويات الجديد كنسب مئوية. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | يعيد حجم محتويات صفحات الوثيقة. يتم تقليص محتويات الصفحة وإضافة هوامش. يتم تحديد حجم المحتويات الجديد كنسب مئوية. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | يقسم ملف PDF إلى عدة وثائق. يمكن أن تكون الوثائق ذات صفحة واحدة أو متعددة الصفحات. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | يقسم ملف PDF إلى عدة وثائق. يمكن أن تكون الوثائق ذات صفحة واحدة أو متعددة الصفحات. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كملف جديد. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | يقسم ملف PDF إلى وثائق ذات صفحة واحدة. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | يقسم ملف PDF إلى وثائق ذات صفحة واحدة. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | يقسم ملف PDF إلى وثائق ذات صفحة واحدة ويحفظها في المسار المحدد. يتم تحديد المسار بواسطة قالب اسم الحقل. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | يقسم ملف PDF إلى وثائق ذات صفحة واحدة ويحفظها في المسار المحدد. يتم تحديد المسار بواسطة قالب اسم الحقل. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | يضيف الصفحات، التي تم اختيارها من مصفوفة الوثائق في portStreams. تتضمن الوثيقة الناتجة firstInputFile وجميع صفحات وثائق portStreams في النطاق من startPage إلى endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | يضيف الصفحات، التي تم اختيارها من وثائق portFiles. تتضمن الوثيقة الناتجة firstInputFile وجميع صفحات وثائق portFiles في النطاق من startPage إلى endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | يدمج الوثائق. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | يدمج الملفات |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | يدمج الملفات في ملف واحد. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | يدمج ملفين. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | يدمج وثيقتين PDF في وثيقة PDF جديدة مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: تحتوي الوثيقة1 على 5 صفحات: p1، p2، p3، p4، p5. تحتوي الوثيقة2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج وثيقتي PDF إلى إنتاج الوثيقة الناتجة مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | يدمج وثيقتين PDF في وثيقة PDF جديدة مع الصفحات بطرق متناوبة ويملأ الأماكن الفارغة بصفحات فارغة. على سبيل المثال: تحتوي الوثيقة1 على 5 صفحات: p1، p2، p3، p4، p5. تحتوي الوثيقة2 على 3 صفحات: p1'، p2'، p3'. سيؤدي دمج وثيقتي PDF إلى إنتاج الوثيقة الناتجة مع الصفحات: p1، p1'، p2، p2'، p3، p3'، p4، صفحة فارغة، p5، صفحة فارغة. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | يحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | يحذف الصفحات المحددة بواسطة مصفوفة الأرقام من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | يستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | يستخرج الصفحات المحددة بواسطة مصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف PDF جديد. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | يُدخل الصفحات من ملف آخر في ملف PDF الإدخال. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | يُدخل الصفحات من ملف آخر في ملف PDF الإدخال. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | يصنع كتيب من InputStream إلى outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | يصنع كتيب من ملف الإدخال إلى ملف الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | يصنع كتيب من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | يصنع كتيب من inputFile إلى outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | يصنع كتيب مخصص من InputStream الأول إلى outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | يصنع كتيب مخصص من firstInputFile إلى outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | يصنع كتيب من InputStream الأول إلى outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | يصنع كتيب مخصص من firstInputFile إلى outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | يصنع وثيقة N-Up من تدفقات PDF المدخلة إلى outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | يصنع وثيقة N-Up من تدفقات PDF المدخلة المتعددة إلى outputStream. ستحتوي كل صفحة من outputStream على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال بنفس رقم الصفحة. تتراكم الصفحات المتعددة أفقيًا إذا كانت isSidewise true وتتراكم عموديًا إذا كانت isSidewise false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | يصنع وثيقة N-Up من ملفي PDF المدخلين إلى outputFile. ستحتوي كل صفحة من outputFile على صفحتين، صفحة واحدة من ملف الإدخال الأول وأخرى من ملف الإدخال الثاني. تتراكم الصفحتان أفقيًا. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | يصنع وثيقة N-Up من ملفات PDF المدخلة المتعددة إلى outputFile. ستحتوي كل صفحة من outputFile على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال بنفس رقم الصفحة. تتراكم الصفحات المتعددة أفقيًا إذا كانت isSidewise true وتتراكم عموديًا إذا كانت isSidewise false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | يصنع وثيقة N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | يصنع وثيقة N-Up من firstInputFile إلى outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | يصنع وثيقة N-Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | يصنع وثيقة N-Up من ملف الإدخال إلى outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | يعيد حجم محتويات صفحات الوثيقة. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | يعيد حجم محتويات الصفحات في الوثيقة. إذا تم تقليص الصفحة، تتم إضافة هوامش فارغة حول الصفحة. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | يعيد حجم محتويات صفحات الوثيقة. يتم تقليص محتويات الصفحة وإضافة هوامش. يتم تحديد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | يقسم ملف PDF من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كملف جديد. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | الإجراء المتخذ عند مواجهة ملف تالف في عملية الدمج. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | فئة لتحديد معلمات تغيير حجم الصفحة. يسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات الفضاء الافتراضية أو كنسب مئوية من حجم الصفحات الأولية؛ الهوامش اليسرى، العلوية، السفلية، واليمنى بوحدات الفضاء الافتراضية أو كنسب مئوية من حجم الصفحة الأولية؛ يمكن ترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من بقية حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض الصفحة الجديدة بـ 60 وحدة، فإن الهوامش اليسرى واليمنى يتم حسابها تلقائيًا: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | قيمة الهامش أو حجم المحتوى المحدد كنسب مئوية من وحدات الفضاء الافتراضية. تُستخدم هذه الفئة في ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | فئة توفر معلومات حول الملفات التالفة في وقت الدمج. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | بيانات موضع فاصل الصفحة. |

### انظر أيضًا

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)