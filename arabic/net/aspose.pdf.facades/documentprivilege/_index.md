---
title: DocumentPrivilege
second_title: Aspose.PDF لمرجع .NET API
description: يمثل امتيازات الوصول إلى ملف Pdf. تشير إلىPdfFileSecurity./pdffilesecurity . هناك 4 طرق لاستخدام هذه الفئة 1. استخدام الامتياز المحدد مسبقًا مباشرة. 2. استنادًا إلى امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. استنادًا إلى امتياز محدد مسبقًا وتغيير بعض مجموعة أذونات Adobe Professional المحددة. 4. يخلط الطريقة 2 والطريقة 3.
type: docs
weight: 2240
url: /ar/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

يمثل امتيازات الوصول إلى ملف Pdf. تشير إلى[`PdfFileSecurity`](../pdffilesecurity) . هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتياز المحدد مسبقًا مباشرة. 2. استنادًا إلى امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. استنادًا إلى امتياز محدد مسبقًا وتغيير بعض مجموعة أذونات Adobe Professional المحددة. 4. يخلط الطريقة 2 والطريقة 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | الكل مسموح به. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | يسمح بملف التجميع. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | يسمح بنسخ الملف. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | يسمح بطباعة متدهورة . |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | يسمح بملء النماذج في الملف. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | جميع ممنوع. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | يسمح بتعديل التعليقات التوضيحية للملف. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | يسمح بتعديل الملف. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | يسمح بطباعة الملف. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | يسمح بالقراءة على الشاشة فقط. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | يحدد الإذن الذي يسمح بالتجميع أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | يحدد الإذن الذي يسمح بالنسخ أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | يحدد الإذن الذي يسمح بالطباعة المتدهورة أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | يحدد الإذن الذي يسمح بملء النماذج أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | يحدد الإذن الذي يسمح بتعديل التعليقات التوضيحية أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | يحدد الإذن الذي يسمح بتعديل المحتويات أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | يحدد الإذن الذي يسمح بالطباعة أم لا. الصواب هو السماح والخطأ ممنوع. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | يحدد الإذن الذي يسمح بقارئات الشاشة أم لا. الصواب هو السماح والخطأ ممنوع. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | يضبط مستوى تغيير امتياز المستند. تمامًا مثل الإعدادات المسموح بها لتغييرات Adobe Professional . 0: لا شيء . 1: إدراج الصفحات وحذفها وتدويرها . 2: ملء حقول النموذج وتوقيع حقول التوقيع الموجودة. 3: التعليق وملء حقول النموذج والتوقيع الموجود حقول التوقيع . 4: أي باستثناء صفحات الاستخراج. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | يضبط مستوى نسخ امتياز المستند. تمامًا مثل إعدادات أذونات Adobe Professional . 0: بلا . 1: تمكين الوصول إلى النص لأجهزة قراءة الشاشة للمعاقين بصريًا . 2: تمكين نسخ النص والصور والمحتويات الأخرى . |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | يضبط مستوى طباعة امتياز المستند. تمامًا مثل الإعدادات المسموح بها للطباعة في Adobe Professional . 0: بلا. 1: دقة منخفضة (150 نقطة في البوصة) . 2: دقة عالية . |

## طُرق

| اسم | وصف |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | يقارن اثنين[`DocumentPrivilege`](../documentprivilege) الكائنات .  الكائن المراد مقارنته . عدد صحيح بعلامة يشير إلى القيم النسبية لهذا المثيل والقيمة. أقل من صفر هذا المثال أقل من القيمة. هذا المثال يساوي صفرًا. هذا المثيل أكبر من الصفر أكبر من القيمة. |

### أمثلة

```csharp
[C#]	
// Way1: استخدام الامتياز المحدد مسبقًا مباشرة.
DocumentPrivilege privilege = DocumentPrivilege.Print;

// Way2: استنادًا إلى امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

// Way3: استنادًا إلى امتياز محدد مسبقًا وتغيير بعض مجموعات أذونات Adobe Professional المحددة.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

// Way4: تمزج بين way2 و way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'الطريقة 1: استخدام الامتياز المحدد مسبقًا مباشرة.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: استنادًا إلى امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: استنادًا إلى امتياز محدد مسبقًا وتغيير بعض مجموعات أذونات Adobe Professional المحددة.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: تمزج way2 و way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
