---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.DocumentPrivilege. تمثل الامتيازات للوصول إلى ملف Pdf. راجع PdfFileSecurity. هناك 4 طرق لاستخدام هذه الفئة 1. استخدام الامتيازات المعرفة مسبقًا مباشرة. 2. بناءً على امتياز معرف مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز معرف مسبقًا وتغيير بعض تركيبات أذونات Adobe Professional المحددة. 4. مزج الطريقة 2 والطريقة 3
type: docs
weight: 4230
url: /ar/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

تمثل الامتيازات للوصول إلى ملف Pdf. راجع [`PdfFileSecurity`](../pdffilesecurity/). هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتيازات المعرفة مسبقًا مباشرة. 2. بناءً على امتياز معرف مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز معرف مسبقًا وتغيير بعض تركيبات أذونات Adobe Professional المحددة. 4. مزج الطريقة 2 والطريقة 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Properties

| Name | Description |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | جميعها مسموح بها. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | يسمح بتجميع الملف. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | يسمح بنسخ الملف. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | يسمح بالطباعة المنخفضة الجودة. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | يسمح بملء النماذج في الملف. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | جميعها ممنوعة. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | يسمح بتعديل التعليقات التوضيحية للملف. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | يسمح بتعديل الملف. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | يسمح بطباعة الملف. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | يسمح بالقراءة على الشاشة فقط. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | يحدد الإذن الذي يسمح بالتجميع أو لا. true يسمح و false ممنوع. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | يحدد الإذن الذي يسمح بالنسخ أو لا. true يسمح و false ممنوع. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | يحدد الإذن الذي يسمح بالطباعة المنخفضة الجودة أو لا. true يسمح و false ممنوع. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | يحدد الإذن الذي يسمح بملء النماذج أو لا. true يسمح و false ممنوع. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | يحدد الإذن الذي يسمح بتعديل التعليقات التوضيحية أو لا. true يسمح و false ممنوع. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | يحدد الإذن الذي يسمح بتعديل المحتويات أو لا. true يسمح و false ممنوع. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | يحدد الإذن الذي يسمح بالطباعة أو لا. true يسمح و false ممنوع. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | يحدد الإذن الذي يسمح بقراءة الشاشة أو لا. true يسمح و false ممنوع. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | يحصل على مستوى تغيير امتيازات الوثيقة ويضبطه. تمامًا كما في إعدادات Adobe Professional لتغييرات المسموح بها. 0: لا شيء. 1: إدراج، حذف وتدوير الصفحات. 2: ملء حقول النموذج وتوقيع حقول التوقيع الموجودة. 3: التعليق، ملء حقول النموذج، وتوقيع حقول التوقيع الموجودة. 4: أي شيء باستثناء استخراج الصفحات. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | يحصل على مستوى النسخ لامتيازات الوثيقة ويضبطه. تمامًا كما في إعدادات أذونات Adobe Professional. 0: لا شيء. 1: تمكين الوصول إلى النص لأجهزة قراءة الشاشة للمكفوفين. 2: تمكين نسخ النصوص والصور والمحتويات الأخرى. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | يحصل على مستوى الطباعة لامتيازات الوثيقة ويضبطه. تمامًا كما في إعدادات Adobe Professional للطباعة المسموح بها. 0: لا شيء. 1: دقة منخفضة (150 نقطة في البوصة). 2: دقة عالية. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | يقارن بين كائنين من `DocumentPrivilege`. الكائن الذي سيتم المقارنة به. عدد صحيح موقع يشير إلى القيم النسبية لهذه الحالة والقيمة. أقل من الصفر هذه الحالة أقل من القيمة. صفر هذه الحالة تساوي القيمة. أكبر من الصفر هذه الحالة أكبر من القيمة. |

## Examples

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
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

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)