---
title: "Aspose.Pdf.Annotations"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "يوفر مساحة الأسماء Aspose.Pdf.Annotations فئات للعمل مع أنواع مختلفة من إجراءات الوجهات وغيرها من ميزات المستند التي تُسمى تقليديًا تفاعلية، مما يتيح للمستخدم التفاعل معه."
type: docs
weight: 50
url: /ar/net/aspose.pdf.annotations/
---
توفر مساحة الاسم **Aspose.Pdf.Annotations** فئات للعمل مع أنواع مختلفة من الإجراءات والوجهات وغيرها من ميزات المستند التي تُسمى تقليديًا تفاعلية، مما يتيح للمستخدم التواصل معه.

## الفئات

| فئة | الوصف |
| --- | --- |
| [ActionCollection](./actioncollection/) | مجموعة من الإجراءات |
| [Annotation](./annotation/) | فئة تمثل كائن التعليق التوضيحي. |
| [AnnotationActionCollection](./annotationactioncollection/) | يمثل مجموعة إجراءات التعليقات التوضيحية. |
| [AnnotationCollection](./annotationcollection/) | فئة تمثل مجموعة التعليقات التوضيحية. |
| [AnnotationSelector](./annotationselector/) | تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة نموذج الزائر. |
| [AppearanceDictionary](./appearancedictionary/) | قاموس مظهر التعليق التوضيحي يحدد كيفية عرض التعليق بصريًا على الصفحة. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | يمثل تعليق توضيحي لعلامة النزيف. |
| [Border](./border/) | فئة تمثل خصائص حدود التعليق التوضيحي. |
| [CaretAnnotation](./caretannotation/) | فئة تمثل تعليق توضيحي للمؤشر. |
| [Characteristics](./characteristics/) | يمثل خصائص التعليق التوضيحي |
| [CircleAnnotation](./circleannotation/) | فئة تمثل تعليق توضيحي دائري. |
| [ColorBarAnnotation](./colorbarannotation/) | فئة تمثل تعليقًا توضيحيًا من نوع ColorBarAnnotation. يتم تجاهل الخاصية Color، ويتم استخدام لون ColorsOfCMYK بدلاً منها. عند الإنشاء، يحدد نسبة العرض إلى الارتفاع اتجاه التعليق — أفقي أو عمودي. بعد ذلك، يتم التحقق من أن مستطيل التعليق خارج TrimBox، وإذا لم يكن كذلك، يتم إزاحته إلى أقرب موقع خارج TrimBox مع مراعاة اتجاه التعليق. يمكن تقليل العرض (الارتفاع) بحيث يتناسب التعليق خارج TrimBox. إذا لم يتوفر مساحة للتخطيط، يمكن ضبط العرض/الارتفاع على الصفر (في هذه الحالة، يكون التعليق موجودًا على الصفحة لكنه غير معروض). |
| [CommonFigureAnnotation](./commonfigureannotation/) | فئة تجريدية تمثل تعليقًا توضيحيًا شائعًا. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | يمثل أنواع التعليقات التوضيحية التي توضع في زوايا الصفحة المطبوعة. |
| [CustomExplicitDestination](./customexplicitdestination/) | يمثل وجهة صريحة مخصصة. |
| [Dash](./dash/) | فئة تمثل نمط الخط المتقطع. |
| [DefaultAppearance](./defaultappearance/) | يصف المظهر الافتراضي للحقل (الخط، حجم النص واللون). |
| [DocumentActionCollection](./documentactioncollection/) | الفئة تصف الإجراءات التي تُجرى على بعض الإجراءات مع المستند. |
| [ExplicitDestination](./explicitdestination/) | يمثل الفئة الأساسية للوجهات الصريحة في مستند PDF. |
| [FdfReader](./fdfreader/) | فئة تقوم بقراءة تنسيق FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | الفئة تصف ملاحظة مرفق الملف. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع تكبير محتواها بما يكفي لتلائم الصندوق المحيط بها بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع تمركز الصندوق المحيط داخل النافذة في البُعد الآخر. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع وضع الإحداثي العمودي العلوي عند حافة النافذة العليا وتكبير محتوى الصفحة بما يكفي لتلائم العرض الكامل لصندوقها المحيط داخل النافذة. قيمة null للعلوي تشير إلى أن القيمة الحالية لهذا المعامل يجب الاحتفاظ بها دون تغيير. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع وضع الإحداثي الأفقي الأيسر عند حافة النافذة اليسرى وتكبير محتوى الصفحة بما يكفي لتلائم الارتفاع الكامل لصندوقها المحيط داخل النافذة. قيمة null للأيسر تشير إلى أن القيمة الحالية لهذا المعامل يجب الاحتفاظ بها دون تغيير. |
| [FitExplicitDestination](./fitexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع تكبير محتواها بما يكفي لتلائم الصفحة بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع تمركز الصفحة داخل النافذة في البُعد الآخر. |
| [FitHExplicitDestination](./fithexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع وضع الإحداثي العمودي العلوي عند حافة النافذة العليا وتكبير محتوى الصفحة بما يكفي لتلائم العرض الكامل للصفحة داخل النافذة. قيمة null للعلوي تشير إلى أن القيمة الحالية لهذا المعامل يجب الاحتفاظ بها دون تغيير. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع تكبير محتواها بما يكفي لتلائم المستطيل المحدد بالإحداثيات اليسار، الأسفل، اليمين، والعلوي بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع تمركز المستطيل داخل النافذة في البُعد الآخر. قد يؤدي قيمة null لأي من المعاملات إلى سلوك غير متوقع. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة مع وضع الإحداثي الأفقي الأيسر عند حافة النافذة اليسرى وتكبير محتوى الصفحة بما يكفي لتلائم الارتفاع الكامل للصفحة داخل النافذة. قيمة null للأيسر تشير إلى أن القيمة الحالية لهذا المعامل يجب الاحتفاظ بها دون تغيير. |
| [FixedPrint](./fixedprint/) | يمثل بيانات الطباعة الثابتة لتعليق العلامة المائية. |
| [FreeTextAnnotation](./freetextannotation/) | يمثل ملاحظة نص حر تعرض النص مباشرة على الصفحة. على عكس ملاحظة النص العادية، لا تمتلك ملاحظة النص الحر حالة فتح أو إغلاق؛ بدلاً من عرضها في نافذة منبثقة، يكون النص دائماً مرئياً. |
| [GoToAction](./gotoaction/) | يمثل إجراء الانتقال إلى الذي يغيّر العرض إلى وجهة محددة (صفحة، موقع، وعامل التكبير). |
| [GoToRemoteAction](./gotoremoteaction/) | يمثل إجراء الانتقال إلى عن بُعد الذي يشبه إجراء الانتقال إلى العادي لكنه ينتقل إلى وجهة في ملف PDF آخر بدلاً من الملف الحالي. |
| [GoToURIAction](./gotouriaction/) | يمثل إجراء URI الذي يتسبب في حل URI. |
| [HideAction](./hideaction/) | يمثل إجراء إخفاء يخفى أو يظهر ملاحظة أو أكثر على الشاشة عن طريق تعيين أو مسح علامات الإخفاء الخاصة بها. |
| [HighlightAnnotation](./highlightannotation/) | يمثل ملاحظة تمييز تُبرز نطاقاً من النص في المستند. |
| [ImportDataAction](./importdataaction/) | عند استدعاء إجراء استيراد البيانات، يجب استيراد بيانات تنسيق بيانات النماذج (FDF) إلى النموذج التفاعلي للمستند من ملف محدد. |
| [InkAnnotation](./inkannotation/) | يمثل "خربشة" يدوية تتكون من مسار أو أكثر غير متصلة. |
| [JavascriptAction](./javascriptaction/) | فئة تمثل إجراء جافاسكريبت. |
| [LaunchAction](./launchaction/) | يمثل إجراءً للإطلاق يقوم بتشغيل تطبيق أو فتح أو طباعة مستند. |
| [LineAnnotation](./lineannotation/) | فئة تمثل تعليقا خطيًا. |
| [LinkAnnotation](./linkannotation/) | يمثل إما رابطًا تشعبيًا إلى هدف في مكان آخر داخل المستند أو إجراءً يجب تنفيذها. |
| [MarkupAnnotation](./markupannotation/) | فئة مجردة تمثل تعليقا للعلامات. |
| [Measure](./measure/) | فئة تصف نظام إحداثيات القياس. |
| [MediaClip](./mediaclip/) | فئة تصف كائن مقطع وسائط للعرض. |
| [MediaClipData](./mediaclipdata/) | فئة تصف بيانات مقطع وسائط. |
| [MediaClipSection](./mediaclipsection/) | هذه الفئة تصف قسم مقطع الوسائط. |
| [MediaRendition](./mediarendition/) | فئة تصف عرض الوسائط. |
| [MovieAnnotation](./movieannotation/) | يمثل تعليقا للفيلم يحتوي على رسومات متحركة وصوت يُعرض على شاشة الكمبيوتر ومن خلال السماعات. عند تفعيل التعليق، يتم تشغيل الفيلم. |
| [NamedAction](./namedaction/) | يمثل إجراءات مسماة من المتوقع أن تدعمها تطبيقات عارض PDF. |
| [NamedDestination](./nameddestination/) | بدلاً من تعريفه مباشرةً باستخدام الصياغة الصريحة، يمكن الإشارة إلى الهدف بصورة غير مباشرة عبر كائن اسم أو سلسلة بايت. |
| [PageInformationAnnotation](./pageinformationannotation/) | يمثل تعليقا لمعلومات الصفحة في مستند PDF. يحتوي هذا التعليق على اسم الملف ورقم الصفحة وتاريخ ووقت إنشاء التعليق. |
| [PDF3DAnnotation](./pdf3dannotation/) | فئة PDF3DAnnotation. لا يمكن وراثة هذه الفئة. |
| [PDF3DArtwork](./pdf3dartwork/) | فئة PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | فئة PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | فئة PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | فئة PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | فئة PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | فئة PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | فئة PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | فئة PDF3DStream. |
| [PDF3DView](./pdf3dview/) | فئة PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | فئة PDF3DViewArray. |
| [PdfAction](./pdfaction/) | يمثل إجراءً في مستند PDF |
| [PdfActionCollection](./pdfactioncollection/) | الفئة تصف قائمة الإجراءات. |
| [PolyAnnotation](./polyannotation/) | فئة أساسية مجردة للتعليقات التوضيحية المتعددة. |
| [PolygonAnnotation](./polygonannotation/) | الفئة تمثل تعليق توضيحي مضلع. |
| [PolylineAnnotation](./polylineannotation/) | تمثل تعليق توضيحي خط متعدد يشبه المضلع، باستثناء أن القمة الأولى والأخيرة غير متصلة ضمنيًا. |
| [PopupAnnotation](./popupannotation/) | تمثل التعليق التوضيحي المنبثق الذي يعرض النص في نافذة منبثقة للإدخال والتحرير. |
| [PrinterMarkAnnotation](./printermarkannotation/) | فئة مجردة تمثل تعليق توضيحي لعلامة الطابعة. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | يوفر طرق امتداد للتعداد [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | يمثل تعليق توضيحي Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | يمثل تعليق توضيحي علامة التسجيل. |
| [Rendition](./rendition/) | الفئة التي تصف كائن العرض لـ RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | إجراء عرض يتحكم في تشغيل محتوى الوسائط المتعددة. |
| [RichMediaAnnotation](./richmediaannotation/) | الفئة تصف RichMediaAnnotation التي تسمح بدمج بيانات الفيديو/الصوت في مستند PDF. |
| [ScreenAnnotation](./screenannotation/) | تعليق توضيحي شاشة يحدد منطقة من الصفحة يمكن تشغيل مقاطع الوسائط فيها. |
| [SelectorRendition](./selectorrendition/) | الفئة تصف عرض المحدد. |
| [SoundAnnotation](./soundannotation/) | يمثل تعليق توضيحي صوتي يحتوي على صوت مسجل من ميكروفون الحاسوب أو مستورد من ملف. |
| [SoundData](./sounddata/) | يمثل بيانات صوتية تحدد الصوت الذي سيُشغل عند تفعيل التعليق التوضيحي. |
| [SoundSampleData](./soundsampledata/) | يمثل إدخالات إضافية خاصة بكائن صوت (القسم 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | الفئة تمثل تعليق توضيحي مربع. |
| [SquigglyAnnotation](./squigglyannotation/) | يمثل التعليق التوضيحي المتعرج الذي يظهر كخط سفلي متعرج في نص المستند. |
| [StampAnnotation](./stampannotation/) | يمثل تعليق توضيحي ختم مطاطي. هذا النوع من التعليقات التوضيحية يعرض نصًا أو رسومات تبدو كما لو أنها مختومة على الصفحة بختم مطاطي. |
| [StrikeOutAnnotation](./strikeoutannotation/) | يمثل تعليق توضيحي شطب يظهر كشطب في نص المستند. |
| [SubmitFormAction](./submitformaction/) | الفئة التي تصف إجراء إرسال-نموذج. |
| [TextAnnotation](./textannotation/) | يمثل تعليق توضيحي نصي هو 'ملاحظة لاصقة' مرفقة بنقطة في مستند PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | فئة أساسية مجردة لتعليمات التعليقات التوضيحية للعلامات النصية. |
| [TextStyle](./textstyle/) | الفئة تمثل نمط النص في التعليق التوضيحي |
| [TrimMarkAnnotation](./trimmarkannotation/) | يمثل توضيح علامة القص. |
| [UnderlineAnnotation](./underlineannotation/) | يمثل توضيح تسطير يظهر كخط سفلي في نص المستند. |
| [WatermarkAnnotation](./watermarkannotation/) | الفئة تصف كائن توضيح العلامة المائية. |
| [WidgetAnnotation](./widgetannotation/) | الفئة التي تمثل توضيح الودجت. |
| [XfdfReader](./xfdfreader/) | الفئة التي تقوم بقراءة تنسيق XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | يمثل الوجهة الصريحة التي تعرض الصفحة بالإحداثيات (اليسار، الأعلى) الموضوعة في الزاوية العلوية اليسرى للنافذة ومحتوى الصفحة مكبرًا بمعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تشير إلى أن القيمة الحالية لتلك المعلمة يجب الاحتفاظ بها دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | يحدد الزائر لزيارة توضيحات المستند المختلفة. |
| [IAppointment](./iappointment/) | يمثل الواجهة العامة للإجراءات والوجهات. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | مجموعة من العلامات التي تحدد خصائص مختلفة للتوضيح. |
| [AnnotationState](./annotationstate/) | تعداد الحالات التي يمكن ضبط التوضيح الأصلي عليها. |
| [AnnotationStateModel](./annotationstatemodel/) | نموذج الحالة المقابل لحالة التوضيح. |
| [AnnotationType](./annotationtype/) | تعداد أنواع التوضيحات. |
| [BorderEffect](./bordereffect/) | يصف التأثير الذي يجب تطبيقه على حدود التوضيحات. |
| [BorderStyle](./borderstyle/) | يصف نمط حدود التوضيح. |
| [CapStyle](./capstyle/) | نمط نهاية الخط لخط التوضيح بالحبر. |
| [CaptionPosition](./captionposition/) | تعداد موضع تسمية التوضيح. |
| [CaretSymbol](./caretsymbol/) | رمز يُربط بمؤشر الكتابة. |
| [ColorsOfCMYK](./colorsofcmyk/) | الألوان المشمولة في نموذج ألوان CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | يعدّ أنواع الوجهات الصريحة. |
| [FileIcon](./fileicon/) | أيقونة تُستخدم في عرض التوضيح. |
| [FreeTextIntent](./freetextintent/) | يعدّ نوايا التوضيح النص الحر. |
| [HighlightingMode](./highlightingmode/) | يعدّ وضع تمييز التوضيح، وهو التأثير البصري الذي يُستخدم عندما يُضغط زر الفأرة أو يُستمر ضغطه داخل المنطقة النشطة. |
| [Justification](./justification/) | يعدّ أشكال الضبط (المحاذاة) التي تُستخدم في عرض نص التوضيح. |
| [LaunchActionOperation](./launchactionoperation/) | يعدّ العمليات التي تُجرى على المستند أثناء تنفيذ إجراء الإطلاق. |
| [LightingSchemeType](./lightingschemetype/) | تعداد LightingSchemeType: مجموعة من أنواع مخططات الإضاءة. |
| [LineEnding](./lineending/) | يعدّ أنماط نهايات الخط التي سيتم استخدامها في رسم الخط. |
| [LineIntent](./lineintent/) | يعدّ أغراض تعليقات الخط. |
| [PDF3DActivation](./pdf3dactivation/) | تعداد PDF3DActivation: مجموعة من أوضاع تفعيل التعليقات ثلاثية الأبعاد. |
| [PolyIntent](./polyintent/) | يعدّ أغراض تعليقات المضلع أو الخط المتعدد. |
| [PredefinedAction](./predefinedaction/) | يحدد إجراءات مختلفة يمكن تشغيلها من ملف PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | يمثل موضع علامة في زاوية الصفحة. |
| [PrinterMarkSidePosition](./printermarksideposition/) | يمثل موضع علامة تسجيل على الصفحة. |
| [PrinterMarksKind](./printermarkskind/) | يحدد أنواع علامات الطابعة التي ستُضاف إلى المستند. |
| [RenderModeType](./rendermodetype/) | تعداد RenderModeType: مجموعة من أنواع وضعية العرض |
| [RenditionOperation](./renditionoperation/) | العملية التي تُنفّذ عندما يتم تشغيل الإجراء. |
| [RenditionType](./renditiontype/) | التعداد يصف الأنواع الممكنة للـRendition. |
| [ReplyType](./replytype/) | يعدّ أنواع العلاقات ("نوع الرد") بين التعليق وتلك المحددة بـ InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | خيارات تنسيق مقاطع النص في RichText. |
| [SoundEncoding](./soundencoding/) | تنسيق الترميز لبيانات العينة. |
| [SoundIcon](./soundicon/) | يعدّ الأيقونات التي ستُستخدم في عرض التعليق. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | تنسيق الترميز لبيانات عينة الصوت. |
| [StampIcon](./stampicon/) | يعدّ الأيقونات التي ستُستخدم في عرض التعليق. |
| [TextIcon](./texticon/) | يعدّ الأيقونات التي ستُستخدم في عرض التعليق. |


