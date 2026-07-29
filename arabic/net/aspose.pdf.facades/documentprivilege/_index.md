---
title: "الفئة DocumentPrivilege"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Facades.DocumentPrivilege class. تمثّل الامتيازات للوصول إلى ملف Pdf. ارجع إلى PdfFileSecurity. هناك 4 طرق لاستخدام هذه الفئة 1. استخدام الامتياز المحدد مسبقًا مباشرةً. 2. بناءً على امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز محدد مسبقًا وتغيير بعض تركيبة أذونات Adobe Professional المحددة. 4. دمج الطريقة 2 والطريقة 3."
type: docs
weight: 4350
url: /ar/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

يمثل الامتيازات للوصول إلى ملف Pdf. راجع [`PdfFileSecurity`](../pdffilesecurity/). هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتياز المحدد مسبقًا مباشرة. 2. بناءً على امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز محدد مسبقًا وتغيير بعض تركيبة أذونات Adobe Professional المحددة. 4. مزيج بين الطريقة 2 والطريقة 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | مسموح للجميع. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | يسمح بتجميع الملف. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | يسمح بنسخ الملف. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | يسمح بالطباعة المتدهورة. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | يسمح بملء النماذج في الملف. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | ممنوع للجميع. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | يسمح بتعديل التعليقات التوضيحية للملف. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | يسمح بتعديل الملف. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | يسمح بطباعة الملف. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | يسمح بالقراءة على الشاشة فقط. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | يضبط الإذن الذي يسمح بالتجميع أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | يضبط الإذن الذي يسمح بالنسخ أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | يضبط الإذن الذي يسمح بالطباعة المتدهورة أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | يضبط الإذن الذي يسمح بملء النماذج أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | يضبط الإذن الذي يسمح بتعديل التعليقات التوضيحية أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | يضبط الإذن الذي يسمح بتعديل المحتويات أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | يضبط الإذن الذي يسمح بالطباعة أو لا. true يعني مسموح و false يعني ممنوع. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | يضبط الإذن الذي يسمح بقوارئ الشاشة أو لا. true يعني مسموح و false يعني ممنوع. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | يحصل على ويضبط مستوى التغيير لامتياز المستند. تمامًا كما في إعدادات التغييرات المسموح بها في Adobe Professional. 0: لا شيء. 1: إدراج، حذف وتدوير الصفحات. 2: ملء حقول النماذج وتوقيع الحقول الموقعة الموجودة. 3: التعليق، ملء حقول النماذج، وتوقيع الحقول الموقعة الموجودة. 4: أي شيء باستثناء استخراج الصفحات. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | يحصل على ويضبط مستوى النسخ لامتياز المستند. تمامًا كما في إعدادات الأذونات في Adobe Professional. 0: لا شيء. 1: تمكين الوصول النصي لأجهزة قارئ الشاشة للمكفوفين. 2: تمكين نسخ النصوص، الصور وغيرها من المحتوى. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | يحصل على ويضبط مستوى الطباعة لامتياز المستند. تمامًا كما في إعدادات الطباعة المسموح بها في Adobe Professional. 0: لا شيء. 1: دقة منخفضة (150 نقطة في البوصة). 2: دقة عالية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | يقارن كائنين من نوع `DocumentPrivilege`. الكائن للمقارنة معه. عدد صحيح موقع يشير إلى القيم النسبية لهذه العينة والقيمة. أقل من الصفر يعني أن هذه العينة أصغر من القيمة. صفر يعني أن هذه العينة مساوية للقيمة. أكبر من الصفر يعني أن هذه العينة أكبر من القيمة. |

## أمثلة

```csharp
[C#]	
//الطريقة 1: استخدام الامتياز المحدد مسبقًا مباشرة.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//الطريقة 2: بناءً على امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: بناءً على امتياز محدد مسبقًا وتغيير بعض تركيبات أذونات Adobe Professional المحددة.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: يجمع بين way2 و way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### انظر أيضًا

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


